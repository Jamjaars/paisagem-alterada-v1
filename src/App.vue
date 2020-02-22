<template>
<div>
    <header-nav />
  <div id="app">
    <transition name="router-anim" mode="out-in">
    <router-view />
    </transition>
  </div>
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
