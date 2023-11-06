<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/Retrospective">Retrospective</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
nav {
  position: absolute;
  top: 0;
  text-align: center;
  margin-top: 2rem;
  width: 100%;
  font-size: 1.5rem;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  height: auto;

}

nav a {
  display: inline-block;
  padding: 0 1rem;
}


</style>
