<template>
  <div id="app">
    <layout />
  </div>
</template>

<script>
  import './assets/styles/styles.styl'
  import 'alloytouch/full_page/asset/animate.min.css'
  import Layout from './components/Layout/Layout.vue'
  export default {
    name: 'app',
    components: { Layout }
  }
</script>

<style lang="stylus" scoped>
  #app {
    background url("./assets/images/full-bg-btm.png") no-repeat
    background-position center center
    background-size cover
    background-attachment fixed
  }
</style>
