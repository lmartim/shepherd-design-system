<template>
  <div class="subtitle-small">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'SubtitleSmall'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "@bit/lmartim.calamity._variables";
  .subtitle-small {
    text-align: left;
    
    font-size: $font-size-md;
    line-height: $line-height-medium;

    font-family: $font-family-highlight;
    font-weight: $font-weight-medium;
    color: $neutral-color-4;
  }
</style>
