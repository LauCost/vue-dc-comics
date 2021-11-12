<template>
  <main>
    <div class="jumbo"></div>
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
}
</style>