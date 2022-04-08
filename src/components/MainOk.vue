<template>
  <main>
    <div class="jumbotron"></div>
    <button class="first-button">CURRENT SERIES</button>
    <div class="container">
      <GenerateCard
        v-for="(item, index) in products"
        :key="index"
        :linkImage="item.thumb"
        :series="item.series"
      />
      <button>LOAD MORE</button>
    </div>
  </main>
</template>

<script>
import GenerateCard from "@/components/GenerateCard.vue";
export default {
  name: "MainOk",
  props: {
    products: Array,
  },
  components: {
    GenerateCard,
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: rgb(23, 22, 22);
  color: white;
  .container {
    display: flex;
    flex-wrap: wrap;

    padding: 15px;
    justify-content: center;
    button {
      padding: 5px 30px;
      margin-top: 10px;
      background-color: #0c7cec;
      color: white;
      cursor: pointer;
    }
  }
}

.jumbotron {
  height: 400px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-position: top;
}
.first-button {
  position: relative;
  bottom: 15px;
  font-size: 1.2rem;
  background-color: #0c7cec;
  color: white;
  padding: 5px 30px;
  margin-left: 150px;
}
</style>