<template>
  <header>
    <NavBar></NavBar>
  </header>

  <RouterView class="bg-white dark:bg-gray-900" />
</template>

<script setup lang="ts">
import NavBar from '@/components/NavBar.vue'
import { RouterView } from 'vue-router'
</script>

<style scoped>

</style>
