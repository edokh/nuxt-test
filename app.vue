<template>
  <div>
    <h1>Hello from Nuxt</h1>
    <div>{{ temp }}</div>
  </div>
</template>
<script setup>
const { data: temp } = useFetch("https://httpbin.org/get");
</script>
