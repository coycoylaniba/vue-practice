<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="h-12 border-b border-gray-300 px flex items-center gap-4 px-4">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/todo">Todo</RouterLink>
  </header>

  <main>
    <RouterView />
  </main>

  <footer></footer>
</template>
