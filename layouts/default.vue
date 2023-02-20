<template>
  <div>
    <HeaderApp />
    <Nuxt />
    <Sidenav />
  </div>
  
</template>

<script>
import HeaderApp from '~/components/comun/HeaderApp.vue';
import Sidenav from '~/components/comun/Sidenav.vue';


export default {
  components: {
    HeaderApp,
    Sidenav
}
}
</script>

<style


</style>