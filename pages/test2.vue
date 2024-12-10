<template>
  <div>
    <NuxtLink to="/test">
      To Test 1
    </NuxtLink>
  </div>
</template>
<script setup lang="ts">
  onMounted(() => {
    console.log('test2')

  })
</script>
