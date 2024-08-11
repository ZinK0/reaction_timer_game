<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <h1>Reaction Timer Game</h1>
  <p>Click the Box quickly.</p>
  <ReactionBox></ReactionBox>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import ReactionBox from "./components/ReactionBox.vue";

export default {
  name: "App",
  components: {
    ReactionBox,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
