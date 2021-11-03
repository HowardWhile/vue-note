<template>
  <div id="app">
    <DisplayNumbers />
    <AddNumbers />
  </div>
</template>

<script>
import AddNumbers from './components/AddNumbers.vue'
import DisplayNumbers from './components/DisplayNumbers.vue'

export default {
  name: 'App',
  components: {
    AddNumbers,
    DisplayNumbers
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
