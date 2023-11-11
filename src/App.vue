<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <img src="./assets/peaceful-learn.png" style="width: 50px; height: 50px; margin-left: 10px;">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>
  <br>
  <RouterView />
</template>

<style scoped>

</style>
