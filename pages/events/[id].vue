<script setup>
  const route = useRoute()
  console.log('route', route.params.id)

  const nuxt = useNuxtApp()
  console.log('nuxt', nuxt.$router.currentRoute.value.params.id)
</script>

<template>
  <div>Event id: {{ $route.params.id }}</div>
</template>
