<template>
  <div class="mt-4 mb-4flex">
    <h3 class="font-bold text-2xl mb-4 text-black cursor-pointer" @click="isOpen = !isOpen" v-text="title"></h3>
    <div v-show="isOpen">
      <p class="px-8" v-text="body"></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Question',
  props: ['title', 'body'],
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
