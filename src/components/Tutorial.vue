<template>
  <div id="tutorial">
  Así se juega Sudoku !

  La regla básica del Sudoku

Para completar un Sudoku, debes rellenar las casillas vacías de forma que cada fila, cada columna y cada región contengan todos los números del 1 al 9 y que cada número solo aparezca una vez.

Pero no te preocupes, hablaremos de esto detalladamente más adelante.

Primero aprendamos algunos términos del Sudoku.

<div>
	<br>
<h3>Casillas</h3>El Sudoku se juega en una cuadrícula de 81 Casillas formada por 9 filas y 9 columnas.
</div>
<div>
	<br>
<h3>Números dados</h3>Cuando inicias un nuevo Sudoku, algunas casillas ya contienen números.<br>
Estos números se llaman <u>Números dados</u> y no pueden modificarse durante el juego.<br><br>
Todas las casillas restantes están vacías, para que las llenes con los números que elijas.</div>
<div>
	<br>
<h3 >Filas</h3>La cuadrícula tiene 9 <u>Filas</u> numeradas del 1 al 9, de arriba abajo.<br><br>
Por ejemplo, la fila número 2 es la que aparece resaltada aquí.</div>

<div class="hmarginl15">
	<br>
<h3 class="tuh3">Columnas</h3>La cuadrícula también tiene <u>Columnas</u> numeradas del 1 al 9, de izquierda a derecha.<br>
La columna número 2 es la que aparece resaltada.</div>


<div class="hmarginl15">
	<br>
<h3 class="tuh3">Regiones (o Bloques)</h3>El Sudoku también tiene <u>Regiones</u>, a veces llamadas <u>Bloques</u>.<br>
Las regiones son las casillas de 3x3 separadas por las líneas más gruesas de la cuadrícula.<br><br>
Aquí tienes un ejemplo de una región resaltada.</div>
</div>
</template>

<script>
export default {
  name: 'tutorial'
}
</script>
<!-- styling for the component -->
<style>
#tutorial {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
