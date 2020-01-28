<template lang="pug">
  .card.bg-dark.w-100.h-100
    .card__wrapper.h-100.flex.flex--col.justify-content--space-between.px-3.py-5.bg-darker.bb-2.b-primary
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
@media only screen and (min-width: 600px) {
  .card__wrapper {
    margin: 0 10rem;
  }
}
</style>
