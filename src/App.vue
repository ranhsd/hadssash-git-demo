<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <hello-world-two />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldTwo from "./components/HelloWorld2.vue"

export default {
  name: 'App',
  components: {
    HelloWorld,
    HelloWorldTwo
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
