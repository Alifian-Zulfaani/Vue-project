<template>
  <div class="about container">
    <section class="hero"></section>
  </div>
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
  margin-top: 20px;
  border-radius: 10px;
  min-height: 80vh;
  display: flex;
  align-items: center;
  background-image: url("../assets/hero.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}
</style>
