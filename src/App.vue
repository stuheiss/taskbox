<!-- src/App.vue -->

<template>
  <div id="app">
    <inbox-screen />
  </div>
</template>

<script>
import store from "./store.js";
import InboxScreen from "./containers/InboxScreen.vue";

export default {
  name: "app",
  store,
  components: {
    InboxScreen
  }
};
</script>

<style>
@import "./index.css";
</style>
