<!-- SCRIPT -->
<script setup>
  //Funcao para validar formulario
  const validarFormulario = (e) => {
    alert('Formulario enviado!');
    e.preventDefault();
  }
</script>

<!-- HTML -->
<template>
  <form action="https://www.google.com" @submit="validarFormulario">
    <input type="submit" value="enviar">
  </form>
</template>

<!-- CSS -->
<style scoped>
  
</style>
