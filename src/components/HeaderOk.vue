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

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0px;
}
ul {
  display: flex;
  gap: 20px;

  li {
    list-style-type: none;
    font-size: 0.8rem;
    &:hover {
      color: #0c7cec;
      border-bottom: 2px solid #0c7cec;
    }
  }
}
</style>