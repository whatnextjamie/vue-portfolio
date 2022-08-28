<template>
  <header>
    <img
      alt="Vue logo"
      class="logo"
      height="75"
      src="@/assets/logo.svg"
      width="75"
    />
  </header>
  <div v-show="!homePage">Portfolio top navigation here</div>
</template>

<script>
export default {
  computed: {
    homePage() {
      return this.$route.path === "/" || this.$route.path === "/home";
    },
  },
};
</script>
