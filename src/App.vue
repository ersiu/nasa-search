<template>
  <div id="app">
    <search></search>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import Search from './components/Search'

export default {
  name: 'App',
  components: {
    Search: Search
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
