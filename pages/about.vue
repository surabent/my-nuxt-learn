<template>
  <section class="about-page">
    <h1>About Us</h1>
    <p>
      Welcome to our Nuxt.js application! This page provides information about
      our project and team.
    </p>
    <ul>
      <li>Built with Nuxt.js and Vue.js</li>
      <li>Modern, fast, and SEO-friendly</li>
      <li>Created for learning and demonstration purposes</li>
    </ul>
  </section>
</template>

<script setup>
// No script logic needed for this simple about page
</script>

<style scoped>
.about-page {
  max-width: 600px;
  margin: 2rem auto;
  padding: 2rem;
  background: #f9f9f9;
  border-radius: 8px;
}
.about-page h1 {
  margin-bottom: 1rem;
}
.about-page ul {
  margin-top: 1rem;
  padding-left: 1.5rem;
}
</style>
