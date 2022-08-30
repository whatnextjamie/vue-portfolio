<template>
  <footer>
    <h1 class="mt-6-sm">This is the footer component</h1>
  </footer>
</template>

<style lang="scss">
@use "@/styles/base" as *;

footer {
  @include breakpoint(xl) {
    background-color: $primary-color;
    color: $text-color;
  }
}
</style>
