<template>
  <div>
    <h2>Home View</h2>
    <p>Current path: {{ $route.path }}</p>
    <button class="btn btn-primary" @click="$router.push('/about')">
      Go to About
    </button>
  </div>
</template>

<script setup>
import { useRoute } from 'vue-router'

const route = useRoute()
console.log(route.path)
</script>

<style lang="scss" scoped></style>
