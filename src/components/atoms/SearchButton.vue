<template>
  <button class="searchButton"><search-icon></search-icon></button>
</template>

<script>
import SearchIcon from "./SearchIcon.vue";

export default {
  components: { SearchIcon },
};
</script>

<style scoped>
.searchButton {
  height: 100%;
  border: none;
  border-top-right-radius: 0.6rem;
  border-bottom-right-radius: 0.6rem;
  margin-left: 1px;
  background-color: hsla(0, 0%, 100%, 0.15);
}
</style>
