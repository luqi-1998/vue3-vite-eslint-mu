<script setup>
import { ref } from 'vue'
import { RouterView } from 'vue-router'
const state = ref({ name: 'age' })
</script>

<template>
  <RouterView />
</template>

<style scoped>
@media (min-width: 100%) {
}
</style>
