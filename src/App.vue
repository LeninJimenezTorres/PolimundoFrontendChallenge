<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Polimundo"/> -->
    <TitleComponent msg="Polimundo" subtitle="Frontend Challenge"/>
    <TicketsMenu/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TitleComponent from './components/Title.vue'
import TicketsMenu from './components/TicketsMenu.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    TitleComponent,
    TicketsMenu
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
  background-color: #2c3e50;
}
</style>
