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
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

.container {
  max-width: 1180px;
  margin: auto;
}
</style>
