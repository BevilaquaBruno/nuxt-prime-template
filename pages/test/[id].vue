<script setup lang="ts">
  definePageMeta({
    middleware: 'auth'
  });
  const route = useRoute()
</script>

<template>
  <div>
    <Button label="Teste" />
    <p>Current route: {{ route.path }} id: {{ route.params.id }}</p>
  </div>
</template>