<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <logos-world />
</template>

<script>
import LogosWorld from "./components/LogosWorld.vue";

export default {
  name: "App",
  components: {
    LogosWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
