<template>
  <div class="background">
    <div class="cont links flex">
      <div class="col_1">
        <h3>DC COMICS</h3>

        <ul>
          <li>Charcaters</li>
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

      <div class="col_2">
        <h3>DC</h3>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shops Help</li>
          <li>Contact Us</li>
        </ul>
      </div>

      <div class="col_3">
        <h3>SITES</h3>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.background {
  background-image: url("../../assets/img/footer-bg.jpg");
  background-size: cover;

  h3 {
    color: #ffffff;
    margin: 10px 0;
  }
  ul {
    list-style: none;

    li {
      color: #779595;
      margin: 5px 0;
      font-size: 12px;
    }
  }
}

.flex {
  display: flex;
}

.links {
  background-image: url("../../assets/img/dc-logo-bg.png");
  background-repeat: no-repeat;
  background-position: right;
}

.col_1,
.col_3 {
  margin: 60px 0;
}

.col_2 {
  margin: 60px 25px;
}
</style>