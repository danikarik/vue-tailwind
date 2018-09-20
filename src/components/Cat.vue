<template>
  <div class="cat">
    <img v-if="id == 1" alt="Cat logo" class="w-1/4 h-1/4" src="../assets/hero.svg">
    <img v-else alt="Cat logo" class="w-1/4 h-1/4" src="../assets/kitty.svg">
    <h1 class="text-purple-darker">Cat name is {{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'cat',
  props: {
    id: String,
    name: String
  }
}
</script>
