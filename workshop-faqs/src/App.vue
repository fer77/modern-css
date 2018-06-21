<template>
  <div id="app" class="container mx-auto p-8 w-3/5">
    <div class="mt-4 mb-8 text-center">
      <header>
        <h1>FAQ</h1>
        <p>It's okay. From time to time, we all have questions</p>
      </header>
    </div>
    <Accordion title="Crap attack? Don’t have one?"
               body="If I drunk text you and you’re asleep,don’t text me in the morning…that ship has  sailed."/>
    <h1>Mean while somewhere else in the page</h1>
    <Accordion title="Check this out"
               body="Another accordion somewhere else in the page"/>
  </div>
</template>

<script>
import Accordion from './components/Accordion'

export default {
  name: 'App',
  components: {
    Accordion
  }
}
</script>

<style>
@tailwind preflight;
@tailwind utilities;
</style>
