<template>
  <main>
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
</style>