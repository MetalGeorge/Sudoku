<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Miembros del Grupo:</h2>
<ul>
<li> Raúl Vargas Choquilla </li>
<li> Carlos Montellano Barriga </li>
<li> Jorge Escobar Pacheco </li>
</ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Sudoku SPA con Vue.js'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
