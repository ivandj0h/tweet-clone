<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome"/> -->
  <CobaVue test="ini adalah Component CobaVue"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import CobaVue from './components/CobaVue.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    CobaVue
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
