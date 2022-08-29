<template>
  <footer>
    <h1>This is the footer component</h1>
  </footer>
</template>

<style lang="scss">
@use "@/styles/base" as *;

footer {
  @include breakpoint(XL) {
    background-color: $primary-color;
    color: $text-color;
  }
}
</style>
