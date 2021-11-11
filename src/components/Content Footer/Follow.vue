<template>
  <div class="black">
    <div class="cont dispi">
      <button>SIGN-UP NOW!</button>
      <div class="social flex">
        <p>FOLLOW US</p>
        <img src="../../assets/img/footer-facebook.png" alt="" />
        <img src="../../assets/img/footer-twitter.png" alt="" />
        <img src="../../assets/img/footer-youtube.png" alt="" />
        <img src="../../assets/img/footer-pinterest.png" alt="" />
        <img src="../../assets/img/footer-periscope.png" alt="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.black {
  background-color: #303030;
}

button {
  padding: 15px 20px;
  margin: 50px 0;
  background-color: #303030;
  border: 2px solid #0282f9;
  color: #ffffff;
  font-weight: bold;
}

.social {
  align-items: center;

  p {
    color: #0282f9;
    font-weight: bold;
    font-size: 20px;
    margin-right: 10px;
  }

  img {
    margin: 0 10px;
  }
}
</style>