<template>
  <a class="button-primary" :href="link" target="_blank" v-if="link">
    <slot />
  </a>
  <div class="button-primary" v-else>
    <slot />
  </div>
</template>

<script>
export default {
  name: 'ButtonPrimary',
  props: {
    link: {
      type: String
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "@bit/lmartim.calamity._variables";
  .button-primary {
    display: inline-flex;
    text-decoration: none;

    font-size: $font-size-sm;
    line-height: $line-height-tight;
    border-radius: $radius-size-none;
    padding: $spacing-squish-size-xs-v $spacing-squish-size-xs-h;

    font-family: $font-family-highlight;
    font-weight: $font-weight-medium;
    color: $neutral-color-1;
    background-color: $brand-color-primary-3;

    &:hover {
      cursor: pointer;
      
      background-color: $brand-color-primary-4;
    }
  }
</style>
