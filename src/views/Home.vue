<template>
  <div class="home">
      <img class="home__brasil" src="../assets/mapa-brasil.png" />
      <section v-for="quadrados in quadrantes" :key="quadrados" :class="quadrados"></section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  data () {
    return {
      quadrantes: [
        "f1",
        "c2",
        "d2",
        "e2",
        "f2",
        "h2",
        "i2",
        "j2",
        "b3",
        "c3",
        "d3",
        "e3",
        "f3",
        "g3",
        "h3",
        "i3",
        "j3",
        "k3",
        "l3"
      ]
    };
  },
  components: {
  }
};
</script>
