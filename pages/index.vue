<template>
  <div class="container">

    <headerArea/>

    <contentArea/>

    <footerArea/>

  </div>
</template>

<script>
  import headerArea from '../components/headerArea.vue';
  import contentArea from '../components/contentArea.vue';
  import footerArea from '../components/footerArea.vue';

  export default {
    components: {
      headerArea,
      contentArea,
      footerArea
    }
  }
</script>

<style>
  @import './../assets/styles/index.css';
</style>