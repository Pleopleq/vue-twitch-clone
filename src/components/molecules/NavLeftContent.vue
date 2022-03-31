<template>
  <div class="navbar_leftContent">
    <span> <twitch-logo></twitch-logo></span>
    <span class="leftContent_explore">Explorar</span>
    <span> <more-icon></more-icon></span>
  </div>
</template>

<script>
import TwitchLogo from "../atoms/TwitchLogo.vue";
import MoreIcon from "../atoms/MoreIcon.vue";
export default {
  components: { TwitchLogo, MoreIcon },
};
</script>

<style>
.navbar_leftContent {
  display: flex;
  align-items: center;
  color: white;
  font-weight: 600;
  font-size: 1.2rem;
}
.leftContent_explore {
  padding-right: 1rem;
  padding-left: 1rem;
}

.leftContent_explore:hover {
  color: #bf94ff;
}
</style>
