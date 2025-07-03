<template>
  <div>
    <div class="navbar">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </div>
    <div>
      <slot />
    </div>
  </div>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: center;
  background-color: #ecedb0;
  padding: 1rem;
}
.navbar a {
  color: #582704;
  text-decoration: none;
  margin: 0 1rem;
  font-size: 1.2rem;
  font-weight: 700;
}
.navbar a:hover {
  text-decoration: underline;
}
</style>
