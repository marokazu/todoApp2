<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <page-1 msg="this is page1"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Page1 from './components/Page1.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Page1
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
