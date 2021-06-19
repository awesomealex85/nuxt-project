<template>
  <div class="nav-wrap">
    <nav class="navbar nav footer nav-justified">
      <nuxt-link class="nav-item nav-link" to="/">Home</nuxt-link>
      <!-- <a class="nav-item nav-link" href="index.html">Home</a> -->
      <nuxt-link class="nav-item nav-link" to="/recipe">Recipes</nuxt-link>
      <!-- <a class="nav-item nav-link" href="recipes.html">Recipes</a> -->
      <nuxt-link class="nav-item nav-link" to="/about">About</nuxt-link>
      <!-- <a class="nav-item nav-link" href="about.html">About</a> -->
      <nuxt-link class="nav-item nav-link" to="/pantry">Pantry</nuxt-link>
      <!-- <a class="nav-item nav-link" href="pantry.html">Pantry</a> -->
    </nav>
  </div>
</template>

<script>
  export default {
    name: 'Nav',
  }
</script>

<style scoped>
/* nav{
  background: #083d5d;
} */

</style>
