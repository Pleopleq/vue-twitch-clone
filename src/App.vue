<template>
  <div id="app">
    <the-navbar></the-navbar>
    <h1>Holitas</h1>
  </div>
</template>

<script>
import TheNavbar from "./components/organisms/TheNavbar.vue";
export default {
  name: "App",
  components: { TheNavbar },
};
</script>

<style>
* {
  font-family: "Roboto", sans-serif;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
