<!-- SCRIPT -->
<script setup>

//Variavel
let validacao = true;
</script>

<!-- HTML -->
<template>
  <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva Class</p>
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
