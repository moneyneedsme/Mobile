<template>
  <div id="app">
    <head-nav></head-nav>
    <foot-nav></foot-nav>
  </div>
</template>

<script>
import headNav from './components/headNav.vue'
import footNav from './components/footNav.vue'

export default {
  name: 'app',
  components: {
    headNav,
    footNav
  }
}
</script>

<style>
*{
  margin:0px;
  padding:0px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
