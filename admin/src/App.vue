<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <Fine></Fine>
  </div>
</template>

<script>
  import Fine from './components/Fine.vue'

  export default {
    name: 'App',
    components: {
      Fine
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
