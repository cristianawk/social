<template>
  <div id="app">
    <nav-bar cor="green darken-1"></nav-bar>
    <router-view/>
  </div>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'
export default {
  name: 'app',
  components:{
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
