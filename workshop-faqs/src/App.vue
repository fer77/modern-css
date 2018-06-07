<template>
  <div id="app" class="container mx-auto p-8 w-3/5">
    <div class="mt-4 mb-8 text-center">
      <header>
        <h1>FAQ</h1>
        <p>It's okay. From time to time, we all have questions</p>
      </header>
    </div>
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
