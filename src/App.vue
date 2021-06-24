<template>
  <div id="app">
    <Heading />
    <kalkulator />
  </div>
</template>

<script>
import Heading from "./components/Heading.vue";
import kalkulator from "./components/kalkulator.vue";
export default {
  name: "App",
  components: {
    Heading,
    kalkulator,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1471ce;
  margin-top: 30px;
}
</style>


