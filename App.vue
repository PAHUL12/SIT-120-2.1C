<template>
  <div id="app">
    <TodoApp />
  </div>
</template>

<script>
import TodoApp from './components/my-todo-pahul.vue'

export default {
  name: 'App',
  components: {
    TodoApp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>