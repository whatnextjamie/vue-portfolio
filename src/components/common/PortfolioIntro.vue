<script>
export default {
  props: {
    title: String,
    startDate: String,
    endDate: String,
  },
};
</script>

<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
  <div class="intro">
    <h2>About the Project</h2>
    <h3>
      <slot name="about"></slot>
    </h3>
    <p>{{ startDate }}</p>
    <p>{{ endDate }}</p>
  </div>
</template>

<style scoped>
.intro {
  height: 90vh;
}
</style>
