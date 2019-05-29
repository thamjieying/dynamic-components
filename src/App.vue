<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <dynamic-link :type="type" :data="data"></dynamic-link>
  </div>
</template>

<script>
import dynamicLink from "@/components/DynamicLink.vue";
export default {
  name: "app",
  components: {
    dynamicLink
  },
  data() {
    return {
      type: null,
      data: ""
    };
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
