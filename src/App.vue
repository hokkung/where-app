<script>
import NavBar from "./components/NavBar.vue";
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Home
  }
};
</script>

<template>
  <div id="app">
    <NavBar />
    <Home />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@700&display=swap");

html,
body {
  height: 100%;
}
</style>
