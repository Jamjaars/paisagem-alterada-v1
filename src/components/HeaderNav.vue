<template>
  <header class="header--fixed">
    <div class="header__nav">
      <span class="header__title">paisagem-alterada-v1</span>
      <router-link class="header__link" to="/">Home</router-link>
      <router-link class="header__link" to="/about">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderNav"
}
</script>

<style scoped>
@import '../assets/css/mains.css'
</style>
