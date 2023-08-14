<template>
    <div>
        <h1 class="caja-h1">Aprendiendo sobre las Cajas o Box en css</h1>
        <h1 class="caja-h1-2">Aprendiendo relleno externo o margin</h1>
    </div>
    
    <div class="circulo">
        <span>Jugando con border radius</span>
    </div>
    <a href="#" class="margen1">Primer Bloque Inline</a>

    <span class="mi-texto">Segundo Bloque</span>
  
    <button class="margen2">Tercer Bloque</button>

</template>

<script>

    export default {
      // eslint-disable-next-line vue/multi-word-component-names
    name: 'Caja'
    }

</script>

<style lang="css" scoped>

 .caja-h1{
    border:1px solid pink;
    border-radius: 1em;
    text-align: center ;
    color: pink;
    padding: 50px;
    width: 10em;
    height: 10em;
 }

 .caja-h1-2{
    border: 3px solid ;
    border-color: pink;
    color: violet;
    margin-top: 30px;

 }
 .circulo{
    border:1em solid cornflowerblue;
    width: 20em;
    height: 20em;
    border-radius: 50%;
   background-color: deeppink;
 }
 .margen1 {
    display: block;
    margin: 3em 5em 3em 3em
 }

 .margen2{
    padding: 2em 5em 2em 2em;
    background: cornflowerblue;
    border-radius: 20px;
    color: whitesmoke;
   
 }

 .mi-texto{
    display: block;
    padding: 10px 2em 10px 2em;
    background: rgb(233, 212, 91) ;
    color: aliceblue;
    border-radius: 10px ;
    width: 200px ;
    margin: 2em;
    text-align: center;
    font-size: 20px;
 }

</style>
<!-- 1em equivale a 16 px -->