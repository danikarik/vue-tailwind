<template>
  <div class="home">
    <cat id="2" name="Dakosha"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Cat from '@/components/Cat.vue'

export default {
  name: 'about',
  components: {
    Cat
  }
}
</script>
