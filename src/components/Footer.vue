<template>
  <footer>
    <Links />
    <Follow />
  </footer>
</template>

<script lang="ts">
import Links from "./Content Footer/Links.vue";
import Follow from "./Content Footer/Follow.vue";

export default {
  name: "App",
  components: {
    Links,
    Follow,
  },
};
</script>

<style lang="scss">
@import "./Style/variabile.scss";
</style>