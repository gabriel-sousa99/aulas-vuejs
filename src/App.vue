<template>
  <div id="app">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <HelloWorld :msg="msg" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
export default {
  components: {
    HelloWorld,
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js + Vite App",
    };
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
img {
  width: 100px;
  height: 100px;
  margin: auto 30px;
}
</style>
