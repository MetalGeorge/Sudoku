<template>
  <div id="app">
    <h1>Sudoku SPA con Vue.js </h1>
  <router-link v-bind:to="'/'">Home</router-link>
  <router-link v-bind:to="'/Sudoku'">Sudoku</router-link>
  <router-link v-bind:to="'/Tutorial'">Tutorial</router-link>
  <!-- the router outlet, where all matched components would ber viewed -->
  <router-view></router-view>

  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
<!-- styling for the component -->
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
