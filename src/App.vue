<!-- alurapic/src/App.vue -->

<template>

  <div>
    <h1>{{ titulo }}</h1>

    <ul>

      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>

    </ul>

  </div>
</template>

<script>

// agora temos apenas a propriedade `fotos` que é um array que possui dois objetos que possuem as propriedades `url` e `titulo`, cada um com seu valor.
export default {

  data() {
    return {
      titulo: 'Alurapic',
      fotos: []
      

    }
  },

  created()
  {
      alert('Criei o componente!');
  }
}
</script>

<style>
</style>