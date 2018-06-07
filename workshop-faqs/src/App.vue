<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Question/>
  </div>
</template>

<script>
import Question from './components/Question'

export default {
  name: 'App',
  components: {
    Question
  }
}
</script>

<style>
@tailwind preflight;
@tailwind utilities;

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
