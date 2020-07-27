<template>
  <div id="app">
    <Chidera name="Ani Chidera James"/>
  </div>
</template>

<script>
import Chidera from './components/Chidera.vue'

export default {
  name: 'App',
  components: {
    Chidera
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
