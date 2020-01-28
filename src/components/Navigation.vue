<template>
  <div class="navigation">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/about">Proof</router-link>
    <router-link to="/about">Toolkit</router-link>
    <router-link to="/about">Resume</router-link>
    <router-link to="/about">Contact</router-link>
  </div>
</template>

<script>
export default {
  name: 'Navigation'
};
</script>

<style lang="scss">
.navigation {
  display: flex;
}
</style>
