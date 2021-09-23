<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld />
    <NewFile />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NewFile from './components/NewFile.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NewFile
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
