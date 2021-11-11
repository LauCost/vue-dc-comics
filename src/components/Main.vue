<template>
  <main>
    <Content1 />
  </main>
</template>

<script>
import Content1 from "./ContentMain.vue";

export default {
  name: "App",
  components: {
    Content1,
  },
};
</script>


<style lang="scss">
main {
  background-color: black;
}
</style>