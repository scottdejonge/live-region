<script>
export default {
  name: 'LiveRegion',
  props: {}
}
</script>

<template>
  <div
    role="status"
    aria-live="polite"
    aria-atomic="true"
    aria-relevant="text"
  >
    Live area text
  </div>
</template>

<style scoped>
  div {
    padding: 1rem;
    border: 1px solid currentColor;
  }
</style>
