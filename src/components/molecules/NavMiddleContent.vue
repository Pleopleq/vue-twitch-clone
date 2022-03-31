<template>
  <div>
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

<style></style>
