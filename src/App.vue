<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ToDoForm/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import ToDoForm from "./components/ToDoForm";

export default {
  name: "app",
  components: {
    HelloWorld,
    ToDoForm
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
