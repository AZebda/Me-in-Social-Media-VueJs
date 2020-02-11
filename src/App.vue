<template>
  <div id="app">
    <ZebdaAhlem name="ZEBDA AHLEM" role="Fullstack engineer"/>
  </div>
</template>

<script>
import ZebdaAhlem from './components/ZebdaAhlem.vue'

export default {
  name: 'app',
  components: {
    ZebdaAhlem
  }
}
</script>

<style>
#app {
  margin-top: 250px;
  argin-left: auto;
  padding: 30px;
  text-align: center;
}
</style>
