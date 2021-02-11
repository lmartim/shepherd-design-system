<template>
  <div class="shape">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'Shape'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "@bit/lmartim.calamity._variables";
  .shape {
    display: inline-flex;
    
    border-radius: $radius-size-none;
    padding: $spacing-size-lg;
    border-width: $border-size-thin;
    border-style: solid;

    border-color: $neutral-color-2;
    background-color: $neutral-color-1;
  }
</style>
