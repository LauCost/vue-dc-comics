<template>
  <header>
    <div class="cont_img_nav">
      <img src="../assets/img/dc-logo.png" alt="" />
      <NavBar />
    </div>
  </header>
</template>



<script>
import NavBar from "./NavBar.vue";

export default {
  name: "App",
  components: {
    NavBar,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  .cont_img_nav {
    width: 70%;
    margin: auto;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
  }

  img {
    padding: 20px 0;
  }
}
</style>
