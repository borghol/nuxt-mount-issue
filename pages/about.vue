<template>
  <div>
    <h1>About Page</h1>
    <NuxtLink to="/">Go to Home</NuxtLink>
  </div>
</template>
<script setup lang="ts">
  onMounted(() => {
    console.log('about')
  })
definePageMeta({
  cache: true,
});
</script>
