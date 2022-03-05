<template>
  <div id="helpbox-container">
    <router-link to="/home">Home</router-link>
  </div>
</template>

<script>
export default {
  name: "GetHelp",
};
</script>

<style scoped>
#helpbox-container {
  position: absolute;
  z-index: 1;
  width: 100%;
  height: 100vh;
  background: #00478ff8;
}
</style>