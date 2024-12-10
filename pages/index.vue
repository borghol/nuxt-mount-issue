<template>
  <div>
    <h1>Home Page</h1>
    <NuxtLink to="/about">Go to About</NuxtLink>
  </div>
</template>
<script setup lang="ts">
  onMounted(() => {
    console.log('home')
  })

definePageMeta({
  cache: true,
});

</script>
