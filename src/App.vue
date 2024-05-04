<script setup>
import NotFound from './NotFound.vue'
import Register from './Register.vue'
import Home from './Home.vue'
import { ref, computed } from 'vue'



const routes = {
  '/': Home,
  '/register':  Register,
}

const currentPath = ref(window.location.hash)

window.addEventListener('hashchange', () => {
  currentPath.value = window.location.hash
})

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || '/'] || NotFound
})
</script>

<template>
  
  <component :is="currentView" />

</template>

<style scoped>

</style>
