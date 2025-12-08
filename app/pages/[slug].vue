<template>
  <div>
    <h1>[slug] Page</h1>
    <pre>route name: {{ route.name }}</pre>
  </div>
</template>

<script setup lang="ts">
const route = useRoute()
</script>
