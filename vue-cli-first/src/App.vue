<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <h1>La mia prima app con Vue CLI!</h1>
    <h2>Sono un Jumbotron</h2>
    <MyGallery/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyGallery from '.components/MyGallery.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
    MyGallery
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
