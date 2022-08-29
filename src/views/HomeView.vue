<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <main>
    <h1>This is the home view</h1>
    <nav>
      <RouterLink to="/analytics">Analytics</RouterLink>
      <RouterLink to="/design-system">Design System</RouterLink>
    </nav>
  </main>
</template>

<style lang="scss"></style>
