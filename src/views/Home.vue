<template>
  <div class="home">
    <Navigation  />
    <div>
      Hello, world
    </div>
    <div>
      My name is Lisa.
    </div>
    <div>
      A passion for learning has guided me to the
      technology worlds of development, design, marketing.
      So, let's look at what you're working on, I want to know more.
    </div>
    <div>
      We’re going to love working together.
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navigation from "@/components/Navigation.vue";
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    Navigation
  }
};
</script>
