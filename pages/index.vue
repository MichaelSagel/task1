<template>
      <div class="container">

        <headerArea/>

      <contentArea/>

    </div>
</template>

<script>
  import headerArea from '../components/headerArea.vue';
  import contentArea from '../components/contentArea.vue';

  export default {
    components: {
      headerArea,
      contentArea
    }
  }
</script>

<style>
  @import './../assets/styles/index.css';
</style>