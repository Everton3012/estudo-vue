<!-- SCRIPT -->
<script setup>
  const props = defineProps([
    'nome',
    'idade',
    'cidade',
    'vetor',
    'funcao'
  ]);
</script>

<!-- HTML -->
<template>
  <h1>{{ `Nome: ${nome}, Idade: ${idade}, Cidade: ${cidade} ` }}</h1>
  <ul>
    <li v-for="v of vetor">{{ v }}</li>
  </ul>
  <button @click="funcao">Clique aqui</button>
</template>

<!-- CSS -->
<style scoped>
  
</style>
