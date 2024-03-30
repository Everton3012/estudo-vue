<!-- SCRIPT -->
<script setup>
  //Importar componente
  import Exemplo11Props from '@/components/Exemplo11Props2.vue';

  // Variáveis
  let cidade = 'Bahia';
  let cidades = ['São Paulo', 'Rio de Janeiro' , 'Curitiba', 'Florianópolis'];

  // Função
  const mensagem = () => {
    alert('Função criada no componente: Exemplo11Props');
  }
</script>

<!-- HTML -->
<template>
  <Exemplo11Props nome="Everton" idade="23" :cidade="cidade" :vetor="cidades" :funcao="mensagem"/>
</template>

<!-- CSS -->
<style scoped>
  
</style>
