<template>
  <div id="app">
  <router-view />
  </div>
</template>

<script>
   import Home from "./views/Home.vue";


export default {
  name: "App",
  components: {
   Home,
   
  },
};
</script>

<style lang="scss">
html {
  scroll-behavior: smooth;
}

#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;*/
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>