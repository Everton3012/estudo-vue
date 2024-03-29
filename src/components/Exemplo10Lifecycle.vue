<!-- SCRIPT -->
<script setup>

  import {onMounted, ref} from 'vue';

  let texto = ref('hello world!');

  // Lifecycle onMounted
  onMounted(() => {
    setTimeout(() => {
      texto.value = 'texto alterado';
    }, 3000);
  });

</script>

<!-- HTML -->
<template>
  <h1>{{ texto }}</h1>
</template>

<!-- CSS -->
<style scoped>
  
</style>
