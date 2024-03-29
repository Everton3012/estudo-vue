<!-- SCRIPT -->
<script setup>
  //Funcao para validar formulario
  const validarFormulario = () => {
    alert('Formulario enviado!');
  }
</script>

<!-- HTML -->
<template>
  <form @submit="validarFormulario">
    <input type="submit" value="enviar">
  </form>
</template>

<!-- CSS -->
<style scoped>
  
</style>
