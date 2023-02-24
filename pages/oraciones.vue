<template>
  <div class="index-page">
    <oracionesList />
    
  </div>
</template>

<script>

import OracionesList from '~/components/oraciones/OracionesList.vue';
export default {
  name: 'IndexPage',
  components: {
    OracionesList,
    
  },
}
</script>

