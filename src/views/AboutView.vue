<template>
  <div>
    <h2>Abount view</h2>
    <p>Current path: {{ $route.path }}</p>
    <button class="btn btn-primary" @click="goHomePage">Go to Home</button>
  </div>
</template>

<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

const goHomePage = () => {
  router.push('/')
}
</script>

<style lang="scss" scoped></style>
