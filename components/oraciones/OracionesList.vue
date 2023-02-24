<template>
  <div class="oraciones-page">
    <div class="oraciones-content">      
      <div class="header">
        <H1>Oraciones</H1>
        <nuxt-link to="/login"><button>Agregar</button></nuxt-link>
      </div>
      <div class="oraciones">
        <OracionesCard v-for="oracion in oraciones" :key="oracion"/>
      </div>
    </div>
    <idiomas />
  </div>
</template>

<script>
import Idiomas from './idiomas.vue';
import OracionesCard from './OracionesCard.vue';

export default {
    components: { 
      OracionesCard,
        Idiomas
    },
    data() {
      return {
        oraciones: [1,2,3,4]
      }
    }
}
</script>

<style>

</style>