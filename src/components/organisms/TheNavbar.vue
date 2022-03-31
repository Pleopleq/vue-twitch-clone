<template>
  <nav class="navbar">
    <section class="navbar_leftSide">
      <nav-left-content></nav-left-content>
    </section>
    <section class="navbar_middle">
      <nav-middle-content></nav-middle-content>
    </section>
    <section class="navbar_rightSide"></section>
  </nav>
</template>

<script>
import NavLeftContent from "../molecules/NavLeftContent.vue";
import NavMiddleContent from "../molecules/NavMiddleContent.vue";
export default {
  components: { NavLeftContent, NavMiddleContent },
};
</script>

<style>
.navbar {
  display: flex;
  justify-content: space-between;
  background-color: #292d33;
  height: 4rem;
  margin: 0;
  padding: 0;
}
</style>
