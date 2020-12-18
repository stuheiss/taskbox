<!-- src/App.vue -->

<template>
  <div id="app">
    <task-list />
  </div>
</template>

<script>
import store from './store.js';
import TaskList from './containers/TaskList.vue';

export default {
  name: "app",
  store,
  components: {
    TaskList
  }
};
</script>

<style>
  @import './index.css';
</style>
