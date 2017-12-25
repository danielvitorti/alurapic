<template>
  <div>
    <h1>{{titulo}} </h1>
    <img v-bind:src="foto.url" v-bind:alt="foto.titulo" />
  </div>
</template>

<script>
export default {
  
  data () {
    return {
      titulo: 'Alurapic',
      foto:
      {
        url: 'http://tudosobrecachorros.com.br/wp-content/uploads/cachorro-independente.jpg',
        titulo: 'cachorro'
      }
      
    }
  }
}
</script>

<style>

</style>
