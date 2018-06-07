<template>
  <div id="app" class="container mx-auto p-8">
    <Question/>
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
</style>
