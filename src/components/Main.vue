<template>
  <main>
    <div class="jumbo">
      <p class="series">CURRENT SERIES</p>
    </div>
    <Content />
    <Utility />
  </main>
</template>

<script>
import Content from "./Content Main/ContentMain.vue";
import Utility from "./Content Main/Utility.vue";

export default {
  name: "App",
  components: {
    Content,
    Utility,
  },
};
</script>


<style lang="scss">
main {
  background-color: black;
}

.jumbo {
  width: 100%;
  height: 400px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
}

.series {
  background-color: #0282f9;
  padding: 10px 25px;
  text-align: center;
  position: absolute;
  left: 18%;
  bottom: -2%;
  transform: translate(0%, 35%);
  color: #ffffff;
  font-weight: bold;
  font-size: 21px;
}
</style>