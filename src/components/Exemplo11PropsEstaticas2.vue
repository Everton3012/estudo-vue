<!-- SCRIPT -->
<script setup>
  const props = defineProps([
    'nome',
    'idade'
  ]);
</script>

<!-- HTML -->
<template>
  <h1>{{ `Nome: ${nome}, Idade: ${idade}` }}</h1>
</template>

<!-- CSS -->
<style scoped>
  
</style>
