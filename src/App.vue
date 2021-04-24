<template>
  <div>
    <!-- Encapsular el nav en un componente e importarlo -->
    <Nav />
    <!-- ROUTER VIEW QUE CARGARÁ LAS VISTAS (INICIO, SOBRE MÍ, CONTACTO, ETC.) -->
    <router-view></router-view>
    <!-- Footer -->
    <FooterV8 />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue"
import FooterV8 from "@/components/FooterV8.vue";

export default {
  name: "App",
  components: {
    FooterV8,
    Nav,
  },
};
</script>

<style scoped>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
