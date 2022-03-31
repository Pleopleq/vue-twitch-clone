<template>
  <div class="navbar_middleContent">
    <search-bar></search-bar>
    <search-button></search-button>
  </div>
</template>

<script>
import SearchButton from "../atoms/SearchButton.vue";
import SearchBar from "../atoms/SearchBar.vue";

export default {
  components: { SearchButton, SearchBar },
};
</script>

<style>
.navbar_middleContent {
  display: flex;
  height: 4rem;
  width: 27rem;
  align-items: center;
  padding: 0.6rem 0.5rem;
}
</style>
