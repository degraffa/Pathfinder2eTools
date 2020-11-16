<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/pf2e-logo.png">
    <CharacterSelect />
  </div>
</template>

<script>
import CharacterSelect from './components/CharacterSelect.vue'

export default {
  name: 'App',
  components: {
    CharacterSelect
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
