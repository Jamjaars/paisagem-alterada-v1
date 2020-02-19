<template>
  <div id="app">
    <header-nav />
    <router-view />
  </div>
</template>

<script>
import HeaderNav from "./components/HeaderNav.vue";
export default {
  components: {
    HeaderNav
  }
};
</script>

<style>
@import "./assets/css/mains.css";
</style>
