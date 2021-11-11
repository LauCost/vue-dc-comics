<template>
  <div id="app">
    <Header> </Header>
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Greta Sans Condensed Bold", "Greta Sans Bold", Arial, sans-serif;
}
</style>
