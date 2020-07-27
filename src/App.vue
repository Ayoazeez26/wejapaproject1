<template>
  <div id="app">
    <Hakeem
      name="Abdulhakeem"
    />
  </div>
</template>

<script>
import Hakeem from './components/Hakeem.vue'

export default {
  name: 'App',
  components: {
    Hakeem
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
