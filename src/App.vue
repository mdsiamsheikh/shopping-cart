<template>
  <div class="app">
    <Header></Header>
    <div class="container">
      <div class="row"></div>
      <ProducList />
      <CartList />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import ProducList from "./components/ProducList.vue";
import CartList from "./components/CartList.vue";

export default {
  name: "App",
  components: {
    Header,
    ProducList,
    CartList,
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
}
</style>
