<!-- SCRIPT -->
<script setup>
// Vetor
let texto = '<p style="color:red">Aprendendo a diretiva v-html</p>';
</script>

<!-- HTML -->
<template>
  <div v-html="texto"></div>

  <div>{{ texto }}</div>
</template>

<style scoped>

</style>
