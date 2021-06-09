<template>
  <div class="main_component" :style="image">
  </div>
</template>

<script>
export default {
  name: "MainComponent",
  data() {
    return {
      image: { backgroundImage: "url(https://www.tourmag.com/photo/art/grande/35034019-31848358.jpg?v=1561366624)" }
    };
  }
}
</script>

<style scoped>
.main_component {
  margin: 0px;
  padding: 0px;
  height: 100% !important;
  width: 100% !important;
  background-repeat: no-repeat;
  background-size: auto;
  text-align: center;
  background-position: center;
}
</style>
