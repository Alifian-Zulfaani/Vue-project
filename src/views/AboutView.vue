<template>
  <section class="hero"></section>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "HomeView",
  components: {},
};
</script>

<style scoped>
.hero {
  width: 100;
  height: 100vh;
  display: flex;
  align-items: center;
  background-image: url("../assets/hero.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}
</style>
