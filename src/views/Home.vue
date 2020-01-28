<template>
  <div class="home">
    <Card>
      <template v-slot:top>
        Hello, world
      </template>
      <template v-slot:middle>
        <div>
          My name is Lisa.
        </div>
        <div>
          A passion for learning has guided me to the technology worlds of
          development, design, marketing. So, let's look at what you're working
          on, I want to know more.
        </div>
      </template>
      <template v-slot:bottom>
        <div>
          We’re going to love working together.
        </div>
      </template>
    </Card>
  </div>
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
