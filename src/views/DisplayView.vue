<template>
  <section class="login a">
    <div class="w-50 h-100 bg-warning"></div>
    <div class="w-50 h-100 bg-danger"></div>
    <div class="w-50 h-100 bg-primary"></div>
    <div class="w-50 h-100 bg-secondary"></div>
  </section>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "DisplayView",
  components: {},
};
</script>

<style scoped>
.login {
  height: 100vh;
}

.a {
  display: flex;
}
</style>
