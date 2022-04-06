<template>
  <footer>
    <div class="top-footer">
      <div class="container">
        <div class="card">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <p>DIGITAL COMICS</p>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <p>MERCHANDISE</p>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <p>SUBSCRIPTIONS</p>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </div>

    <div class="main-footer">
      <div class="container">
        <div>
          <h3>DC COMICS</h3>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>

        <div>
          <h3>DC</h3>
          <ul>
            <li>Terms Of Use</li>
            <li>Privacy Policy (New)</li>
            <li>AdChoise</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshop</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>

        <div>
          <h3>SITES</h3>
          <ul>
            <li>DC</li>
            <li>MAD Megazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="bottom-footer"></div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.top-footer {
  background-color: #0c7cec;
  padding: 40px;
  .container {
    display: flex;
    justify-content: space-around;
  }
}
.card {
  display: flex;
  align-items: center;
  color: white;
  font-size: 0.8rem;
  img {
    width: 50px;
  }
  p {
    margin-left: 15px;
  }
}
.main-footer {
  background-image: url("../assets/img/footer-bg.jpg");
  padding: 30px 0px;
  .container {
    display: flex;
    max-width: 1180px;
    margin: auto;
  }
  h3 {
    color: white;
    margin-bottom: 10px;
  }
  div {
    margin-right: 25px;
  }
  li {
    margin-top: 5px;
    font-size: 0.8rem;
    list-style-type: none;
    color: grey;
  }
}
</style>