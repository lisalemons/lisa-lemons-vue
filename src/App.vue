<template>
  <div id="app">
    <router-view />
  </div>
</template>


<style lang="scss">
@import './src/assets/vendor/reset';
@import './src/assets/vendor/normalize';
@import './src/assets/vendor/archetype';
@import './src/assets/utilities';

:root {
  --brand-color: #FFBE00;
  --base-gray: #333;
  --darker-gray: #222;
  --border-width: 10px;
  --off-white: #E0E0E0;
}
* {
  box-sizing: border-box;
}
html, body {
  height: 100vh;
  width: 100vw;
}
body {
  color: map-get($colors, 'light');
}
#app {
  height: 100%;
}
</style>
