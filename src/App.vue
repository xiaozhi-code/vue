<template>
  <div id="app">
    <Header></Header>
    <div class="container">
      <Add></Add>
      <List></List>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header";
import Add from "./components/Add";
import List from "./components/List";

export default {
  name: 'App',
  components: {
    Header,
    Add,
    List
  }
}
</script>

<style>
#app {
}
</style>
