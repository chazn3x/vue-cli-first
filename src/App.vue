<template>
  <div id="app">
    <Hero/>
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";

export default {
  name: 'App',
  components: {
    Hero,
  }
}
</script>

<style lang="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
  overflow: hidden;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
