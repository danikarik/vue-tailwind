<template>
  <div class="home">
    <cat id="1" name="Aigosha"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Cat from '@/components/Cat.vue'

export default {
  name: 'home',
  components: {
    Cat
  }
}
</script>
