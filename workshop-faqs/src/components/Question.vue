<template>
  <div class="mt-4 mb-4flex">
    <h3 class="font-bold text-2xl mb-4 text-black cursor-pointer" @click="isOpen = !isOpen">
      Crap attack? Don’t have one?
    </h3>
    <div v-show="isOpen">
      <p class="px-8">If I drunk text you and you’re asleep, don’t text me in the morning…that ship has sailed. The second time hurt the most. My bra’s chafing me. Dear Diary: Tonight I’m sneaking off to the abandoned taffy factory to look for treasure. Also, if boys had uteruses, they’d be called duderuses. Here’s a bunch of numbers. They may look random but they’re my phone number. I’m compiling a list of people I can mate with to repopulate the Earth. uhhhhhhh Yeah it’s an acquired taste. That I just acquired.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Question',
  data () {
    return {
      isOpen: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
