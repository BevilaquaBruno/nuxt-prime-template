<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <i class="pi pi-check"></i>
    <i class="pi pi-times"></i>
    <span class="pi pi-search"></span>
    <span class="pi pi-user"></span>
    <p>Test font in normal weight</p>
    <p class="bold_test">Test font in bold</p>
    <Button label="Success" severity="danger" />
    <h1>Nuxt <b>Routing</b> is active!</h1>
    <p><b>Current route</b>: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a>
  </div>
</template>

<style lang="css">
  .bold_test {
    font-weight: bold;
  }
</style>