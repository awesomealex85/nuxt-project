<template>
  <footer class="">
    <div class="flex__footer">
      <img class="logo " src="../assets/el_comal_logo.png" alt="company logo" />
      <p>Your Guide to Salvadorean Cuisine
      </p>
      <div class="nav-wrap">
        <!-- nuxt routing links -->
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
      <h3>© 2021 Sabores Guanacos, LLC | Seattle, WA
      </h3>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style lang="scss">

</style>
