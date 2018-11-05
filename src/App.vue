<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <Cell /> -->
    <Grid />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import Cell from "./components/Cell.vue";
import Grid from "./components/Grid.vue";

export default {
  name: "app",
  components: {
    // HelloWorld
    // Cell,
    Grid
  }
};
</script>

<style lang="scss">
#app {
  display: flex;
  justify-content: center;
  align-items: center;

  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
