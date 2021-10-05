<template>
  <div id="app">
    <Horloge/>
    <TodoList/>
  </div>
</template>

<script>
import Horloge from './components/Horloge.vue'
import TodoList from './components/TodoList.vue'

export default {
  name: 'App',
  components: {
    Horloge,
    TodoList
  }
}
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
</style>
