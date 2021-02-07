<template>
  <div class="paragraph">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'Paragraph'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "../../../calamity-design-tokens/build/scss/_variables.scss";
  .paragraph {
    font-size: $font-size-xs;
    line-height: $line-height-distant;

    font-family: $font-family-highlight;
    font-weight: $font-weight-regular;
    color: $neutral-color-4;
  }
</style>
