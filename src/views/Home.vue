<template lang="pug">
  .home
    Card
      template(v-slot:top)
        h1.text-primary Hello, world.
      template(v-slot:middle)
        p.
          My name is Lisa.
          A passion for learning has guided me to the technology worlds of
          development, design, marketing. So, let's look at what you're working
          on, I want to know more.
      template(v-slot:bottom)
        h2.text-primary We're going to love working together.
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue';

export default {
  name: 'home',
  components: {
    Card
  }
};
</script>

<style lang="scss" scoped>
.home {
  height: 100%;
}
</style>
