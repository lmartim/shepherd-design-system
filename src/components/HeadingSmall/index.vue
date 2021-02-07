<template>
  <div class="heading-small">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'HeadingSmall'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "../../../calamity-design-tokens/build/scss/_variables.scss";
  .heading-small {
    font-size: $font-size-lg;
    line-height: $line-height-distant;

    font-family: $font-family-highlight;
    font-weight: $font-weight-bold;
    color: $neutral-color-5;
  }
</style>
