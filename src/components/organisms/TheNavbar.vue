<template>
  <nav class="navbar">
    <section class="navbar_leftSide">
      <nav-left-content></nav-left-content>
    </section>
    <section class="navbar_middle"></section>
    <section class="navbar_rightSide"></section>
  </nav>
</template>

<script>
import NavLeftContent from "../molecules/NavLeftContent.vue";
export default {
  components: { NavLeftContent },
};
</script>

<style>
.navbar {
  display: flex;
  justify-content: space-between;
  background-color: #292d33;
  height: 5rem;
  margin: 0;
  padding: 0;
}
</style>
