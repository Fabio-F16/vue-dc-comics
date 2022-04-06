<template>
  <header class="container">
    <div>
      <img src="../assets/img/dc-logo.png" alt="Logo" />
    </div>

    <div>
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0px;
}
ul {
  display: flex;
}
ul li {
  list-style-type: none;
  padding-left: 20px;
  font-size: 0.8rem;
}
</style>