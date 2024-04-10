<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
</template>

<style scoped>
nav {
  background-color: #a4c900;
  padding: 10px 0;
}

nav a {
  margin: 0 10px;
  text-decoration: none;
}
</style>
