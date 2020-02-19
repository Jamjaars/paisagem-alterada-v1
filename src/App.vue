<template>
  <div id="app">
    <header-nav />
    <transition name="router-anim" mode="out-in">
    <router-view />
    </transition>
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
@import "./assets/css/main.css";
</style>
