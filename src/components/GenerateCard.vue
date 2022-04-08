<template>
  <div class="card">
    <img :src="linkImage" />
    <p>{{ series }}</p>
  </div>
</template>

<script>
export default {
  name: "GenerateCard",
  props: {
    linkImage: String,
    series: String,
  },
};
</script>

<style lang="scss" scoped>
.card {
  width: calc(100% / 6);
  img {
    height: 150px;
    width: 150px;
  }
  p {
    margin: 10px 0px;
  }
}
</style>