<!-- SCRIPT -->
<script setup>

const mensagem = () => {
  alert('Trabalhando com eventos de clique!');
}
</script>

<!-- HTML -->
<template>
  <button @click="mensagem">Clique aqui</button>
</template>

<!-- CSS -->
<style scoped>
  .ok{
    color:green;
  }

  .falha{
    color:red;
  }
</style>
