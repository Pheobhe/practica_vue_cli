<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Bienvenido a Vue.js App"/>
  <Cabecera></Cabecera>
  <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quaerat sapiente qui sed soluta id. Veniam sint dolorem ut! Quidem, eaque sit magnam veniam aspernatur eos eius nisi natus tempore distinctio.</p>
</template>



<script>
import HelloWorld from './components/HelloWorld.vue'
import Cabecera from './components/Cabecera.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Cabecera
  }
}

</script>




<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e2a82c;
  margin-top: 60px;
}
</style>
