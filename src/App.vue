<template>
  <div id="app">
    <MainComponent></MainComponent>
    <div>hello Sami ! Nice job !!</div>
  </div>
</template>

<script>
import MainComponent from './components/MainComponent.vue'

export default {
  name: 'App',
  components: {
    MainComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0px;
  padding: 0px;
  height: 50vh;
  width: 100%;
  min-width: 100%;
}
</style>
