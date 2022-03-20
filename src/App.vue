<template>
  <div id="app">
    <img alt="Style No Style logo" src="./assets/vector/default-monochrome.svg" class="w-1 h-1">
    <HelloWorld msg="Style No Style!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import './index.css'
export default {
  name: 'App',
  components: {
    HelloWorld
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
