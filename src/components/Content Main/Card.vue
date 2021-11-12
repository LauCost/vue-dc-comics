<template>
  <div class="card">
    <img :src="image" alt="" />
    <p>{{ serie }}</p>
  </div>
</template>


<script>
export default {
  props: {
    image: String,
    serie: String,
  },
};
</script>

<style lang="scss">
.card {
  width: 12%;
  margin: 30px;

  img {
    width: 100%;
  }
}
p {
  color: #ffffff;
}
</style>