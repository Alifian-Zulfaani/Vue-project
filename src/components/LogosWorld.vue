<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logos</h2>
    <div class="item-logos">
      <img class="logos" alt="adidas logo" src="../assets/adidas-logo.png" />
    </div>
    <div class="item-logos">
      <img class="logos" alt="nike logo" src="../assets/nike-logo.png" />
    </div>
    <div class="item-logos">
      <img class="logos" alt="puma logo" src="../assets/puma-logo.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "LogosWorld",
};
</script>

<style scoped>
.title-header {
  margin-bottom: 80px;
}

.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
  background: navajowhite;
}

.item-logos {
  float: left;
  margin-bottom: 20px;
  margin-right: 20px;
  width: 150px;
  height: 150px;
  background: yellowgreen;
}

.item-logos .logos {
  width: 150px;
  height: 150px;
}
</style>
