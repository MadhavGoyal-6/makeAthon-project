<template>
  <div id="navbar-container">
    <router-link to="/home">Home</router-link>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
#navbar-container {
  background: red;
  width: 100%;
  height: 100px;
}
</style>