<script setup>
//importacion del card principal
//import CardPrincipal from './CardPrincipal.vue';
//importacion del primer card
//import Card from './Card.vue';
import paginaweb from './paginaweb.vue';
import encabezado from './encabezado.vue';
</script>

<template>
<div class="container bg-light p-4 rounded">
  <h1 class="text-center">MASCOTAS</h1>
  <CardPrincipal/>
<Card/>

<Card/> 
</div>

<paginaweb/>
<encabezado/>
</template>

<style scoped>
.container {
  background-color: #e3f2fd;
  padding: 20px;
  border-radius: 10px;
}
.card {
  background-color: #fff3cd;
}
.card h6, .card p {
  font-family: 'Arial', sans-serif;
}
.equal-card {
  height: 100%;
}
</style>
