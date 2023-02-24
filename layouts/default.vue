<template>
  <div class="defaul-layout">
    <HeaderApp />
    <div class="content">
      <Sidenav />
      <Nuxt />
    </div>
  </div>
  
</template>

<script>
import HeaderApp from '~/components/common/HeaderApp.vue';
import Sidenav from '~/components/common/Sidenav.vue';


export default {
  components: {
    HeaderApp,
    Sidenav
}
}
</script>

<style


</style>