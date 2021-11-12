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
  width: 13%;
  margin: 30px 15px;

  img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    object-position: top;
  }

  p {
    margin: 15px 0;
    color: #ffffff;
    font-size: 12.5px;
  }
}
</style>