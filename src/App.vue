<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <div class="w-[1200px]">
    <NavBar />
    <RouterView />
  </div>
</template>

<style scoped></style>
