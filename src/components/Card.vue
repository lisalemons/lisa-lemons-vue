<template lang="pug">
  .card
    .card__wrapper
      .card__top
        slot(name='top')
      .card__middle
        slot(name='middle')
      .card__bottom
        slot(name='bottom')
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.card {
  background: var(--base-gray);
  height: 100%;
  width: 100%;

  &__wrapper {
    background: var(--darker-gray);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    border-bottom: var(--border-width) var(--brand-color) solid;
  }
}
@media only screen and (min-width: 600px) {
  .card__wrapper {
    margin: 0 10rem;
  }
}
</style>
