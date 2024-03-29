<!-- SCRIPT -->
<script setup>

const mensagem = () => {
  alert('Executando a função!');
}
</script>

<!-- HTML -->
<template>
  <input type="text" @keyup.enter="mensagem">
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
