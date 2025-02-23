<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <h1>Index.vue</h1>
    <p>Current route: {{ route.path }}</p>
  </div>
</template>
