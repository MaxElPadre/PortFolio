<template>
  <div id="app">
    <img src="./assets/logo.png">
        <div>
      <navBar></navBar>
    </div>
    <router-view/>

  </div>
</template>

<script>
import NavBar from './Components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
