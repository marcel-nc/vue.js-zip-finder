<template>
  <div id="app">
    
    <zip/>
  </div>
</template>

<script>
import zip from'./components/zip'
export default {
  name: 'app',
  components: {
    zip
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
