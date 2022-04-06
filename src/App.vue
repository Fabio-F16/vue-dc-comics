<template>
  <div id="app">
    <HeaderOk />
    <MainOk />
    <FooterOk />
  </div>
</template>

<script>
import HeaderOk from "./components/HeaderOk.vue";
import MainOk from "./components/MainOk.vue";
import FooterOk from "./components/FooterOk.vue";

export default {
  name: "App",
  components: {
    HeaderOk,
    MainOk,
    FooterOk,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
