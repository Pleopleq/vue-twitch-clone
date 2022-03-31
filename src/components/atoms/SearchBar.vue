<template>
  <input class="searchBar" type="text" placeholder="Buscar" />
</template>

<style scoped>
.searchBar {
  width: 100%;
  height: 100%;
  padding: 0.5rem 1rem;
  border: none;
  border-top-left-radius: 0.6rem;
  border-bottom-left-radius: 0.6rem;
  background-color: hsla(0, 0%, 100%, 0.2);
  color: #efeff1;
  font-size: 1rem;
}

.searchBar::placeholder {
  color: #efeff1;
  font-size: 1rem;
}
</style>
