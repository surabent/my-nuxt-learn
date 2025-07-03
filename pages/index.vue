<template>
  <section class="home">
    <h1>Welcome to Nuxt Learn</h1>
    <p>This is the home page of your Nuxt.js application.</p>
    <nuxt-link to="/about">Learn more about us</nuxt-link>
  </section>
</template>

<script setup>
// No script logic needed for this simple home page
</script>

<style scoped>
.home {
  max-width: 600px;
  margin: 2rem auto;
  text-align: center;
}
h1 {
  color: #2c3e50;
}
</style>
