<!-- SCRIPT -->
<script setup>

  //Importações
  import {onMounted, ref} from 'vue';

  //Vetor contendo as postagens
  let vetor = ref([]);

  // OnMounted
  onMounted(() => {
    fetch('https://jsonplaceholder.typicode.com/posts').then(res => res.json()).then(res => vetor.value = res)
  });
</script>

<!-- HTML -->
<template>
    <h1>
      Requisições
    </h1>

    <table>
      <tr v-for="v in vetor">
        <td>{{ v.userId }} </td>
        <td>{{ v.id  }} </td>
        <td>{{ v.title  }} </td>
        <td>{{ v.body  }} </td>
      </tr>
    </table>
</template>

<!-- CSS -->
<style scoped>
  
</style>
