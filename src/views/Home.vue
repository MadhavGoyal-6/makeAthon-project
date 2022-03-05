<template>
  <div id="home-container">
    <GetHelp />
    <Navbar />
    <div id="gallery"></div>
    <div id="contact-us"></div>
    <div id="categories"></div>
    <div id="reviews"></div>
    <div id="about-us"></div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import GetHelp from "@/components/GetHelp";

export default {
  name: "Home",
  components: {
    Navbar,
    GetHelp,
  },
};
</script>

<style scoped>
#home-container {
  height: 100%;
  width: 100%;
}
#gallery {
  width: 100%;
  height: 500px;
  background: #2c3e50;
}
</style>