<!-- SCRIPT -->
<script setup>
// Variaveis

let exibir = true;
let media = 0.5;
</script>

<!-- HTML -->
<template>
  <h1 v-if="exibir">Hello World!</h1>

  <p v-if="media >= 7">Aprovado(a)</p>
  <p v-else-if="media >= 5 ">Em exame</p>
  <p v-else>Reprovado(a)</p>
</template>

<style scoped>

</style>
