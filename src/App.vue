<template>
  <div id="app">
    <NavbarMenu></NavbarMenu>
    <br>
    <br>
    <br>
    <br>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavbarMenu from './components/NavbarMenu.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavbarMenu
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
