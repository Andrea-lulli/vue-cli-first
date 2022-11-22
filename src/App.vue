<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <AppTitle />
    <div id="Apphero">
    <AppHero />
  </div>
  </div>

  
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'


export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero
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
#Apphero {
  background-color: yellow;
  padding-top: 20px;
  padding-bottom: 20px;
}
</style>
