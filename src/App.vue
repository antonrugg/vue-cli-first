<template>
  <div id="app">
    <JumboTron/>
    <HelloWorld msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import HelloWorld from './components/Title.vue'
import JumboTron from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    JumboTron
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
