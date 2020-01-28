<template>
  <div id="app">
    <router-view />
  </div>
</template>


<style lang="scss">
@import './src/assets/utilities.scss';

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
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Roboto Mono', monospace;
  font-size: 16px;
  line-height: 1.25rem;
  color: map-get($colors, 'light');
}
#app {
  height: 100%;
}
</style>
