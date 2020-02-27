<template>
  <div class="header__wrap" id="div_menu">
    <header class="header--fixed">
      <div class="header__nav">
        <span class="header__title">paisagem-alterada-v1</span>
        <router-link class="header__link" to="/about">About</router-link>
        <router-link class="header__link" to="/">Home</router-link>
      </div>
    </header>
  </div>
</template>

<script>
var div_menu = document.getElementById("div_menu");
window.onscroll = function() {
  if (div_menu)
  div_menu.style.top = window.pageYOffset + "px";
};
export default {
  name: "HeaderNav"
}
</script>
