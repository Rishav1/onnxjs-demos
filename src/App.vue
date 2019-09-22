<template>
  <div id="app">
    <FaceAging/>
  </div>
</template>

<script>
import FaceAging from './components/FaceAging.vue'

export default {
  name: 'app',
  components: {
    FaceAging
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
