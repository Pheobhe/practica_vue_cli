<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Bienvenido a Vue.js App" />
  <Cabecera></Cabecera>

  <Caja /> 
  <flex-box />
  <pie-pagina />
  <card-simple/>
  <person-card/>
  <card-portada/>
  <portada-home/>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import Cabecera from "@/components/Cabecera.vue";
import PiePagina from "@/components/PiePagina.vue";
import Caja from "@/components/practicasCss/Caja.vue";
import FlexBox from "@/components/practicasCss/FlexBox.vue";
import CardSimple from "@/components/practicasCss/CardSimple.vue";
import PersonCard from "@/components/practicasCss/PersonCard.vue";
import CardPortada from "@/components/practicasCss/CardPortada.vue";
import PortadaHome from "@/components/practicasCss/PortadaHome.vue"

export default {
  name: "App",
  components: {
    HelloWorld,
    Cabecera,
    PiePagina,
    Caja,
    FlexBox,
    CardSimple,
    PersonCard,
    CardPortada,
    PortadaHome
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #9b6486;
  margin-top: 60px;
}
</style>
