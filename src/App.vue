<template>
  <div id="app">
    <div class="container">
      <add-todo/>
      <filters-todo/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from "./components/Todos";
import addTodo from "./components/addTodo";
import filtersTodo from "./components/filtersTodo";

export default {
  name: 'app',
  components: {
    Todos,
    addTodo,
    filtersTodo
  }
}
</script>

<style>
body {
  font-family: "Franklin Gotic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
  .container{
    max-width: 1100px;
    margin: auto;
    overflow: auto;
    padding: 0 2rem;
  }
</style>
