<template>
  <div class="index-page">
    <OracionesList />
  </div>
</template>

<script>
import OracionesList from '~/components/oraciones/OracionesList.vue';
export default {
  name: 'IndexPage',
  components: {
    OracionesList
}
}
</script>

