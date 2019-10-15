<template>
  <div id="app" class="reveal">
    <div class="slides">
      <section></section>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Reveal from "reveal.js/js/reveal";

export default {
  name: "app",
  components: {
    //HelloWorld
  },
  mounted() {
    Reveal.initialize();
  }
};
</script>

<style>

@import url("../node_modules/reveal.js/css/reset.css");
@import url("../node_modules/reveal.js/css/reveal.css");
@import url("../node_modules/reveal.js/css/theme/blood.css");

/*#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
