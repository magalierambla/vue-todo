<template>
  <Header :logoSrc="logo" />

  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import logoImg from "./assets/logo.png";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
  },
  computed: {
    logo() {
      return logoImg;
    },
  },
};
</script>

<style module>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
