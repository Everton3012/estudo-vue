<!-- SCRIPT -->
<script setup>
import { ref } from 'vue';

// Vetor
let texto = ref('');
</script>

<!-- HTML -->
<template>
  <input type="text" v-model="texto">
  <p> {{ texto }} </p>
</template>

<style scoped>

</style>
