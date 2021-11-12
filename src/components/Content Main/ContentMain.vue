<template>
  <div class="cont">
    <Cards />
  </div>
</template>

<script>
import Cards from "./Card.vue";

export default {
  components: {
    Cards,
  },
};
</script>




<style lang="scss">
.text_cont {
  color: white;
  font-size: 30px;
  font-weight: 600;
  padding: 50px 0;
}
</style>