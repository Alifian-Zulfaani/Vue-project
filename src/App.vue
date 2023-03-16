<template>
  <nav
    class="navbar navbar-expand-lg justify-content-center fixed-top"
    style="background-color: #2c3e50"
  >
    <router-link to="/">Home</router-link> |
    <router-link to="/profile">Profile</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

nav {
  padding: 10px;
  color: #ffffff;
  top: 0;
  width: 100%;
}

nav a {
  font-weight: bold;
  color: #ffffff;
  text-decoration: none;
  padding-left: 5px;
  padding-right: 5px;
}

nav a.router-link-exact-active {
  color: #13a161;
}
</style>
