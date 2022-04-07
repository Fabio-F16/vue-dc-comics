<template>
  <div id="app">
    <HeaderOk />
    <MainOk :products="cardGame" />
    <FooterOk />
  </div>
</template>

<script>
import HeaderOk from "./components/HeaderOk.vue";
import MainOk from "./components/MainOk.vue";
import FooterOk from "./components/FooterOk.vue";
import cardGame from "@/assets/data/dc-comics.json";

export default {
  name: "App",
  data() {
    return {
      cardGame,
    };
  },
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
