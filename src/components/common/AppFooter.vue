<template>
  <footer class="p-7-lg p-3-xl">
    <h1 class="color-secondary">This is the footer component</h1>
  </footer>
</template>

<style lang="scss">
@use "@/styles/base" as *;

footer {
  @include breakpoint(md) {
    background-color: $color-primary;
  }
}
</style>
