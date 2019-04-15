<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-link class="nav-item" to="/demo">Demo</router-link>
    <button-counter></button-counter>
    <router-view/>
  </div>
</template>

<script>
import ButtonCounter from "@/components/ButtonCounter"
export default {
  name: 'App',
  components:{ButtonCounter }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
