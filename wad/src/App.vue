
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import home from './views/home.vue';
</script>



<template>
  <header>
  
    <div class="wrapper">
        <div class="navbar">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/addPOST">addPOST</RouterLink>
          <RouterLink to="/homepage">homepage</RouterLink>
        </div>
    </div>
  </header>

  <RouterView />
</template>

<style>


</style>
