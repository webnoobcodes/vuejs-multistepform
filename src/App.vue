<template>
  <div id="app">
    <MultiStepForm />
  </div>
</template>

<script>
  import MultiStepForm from './components/MultiStepForm.vue'

  export default {
    components: {
      MultiStepForm
    }
  }
</script>

<style lang="scss">
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-size: 1rem;
    color: #444;
    width: 100%;
    min-height: 100vh;
    overflow: hidden;
  }
</style>
