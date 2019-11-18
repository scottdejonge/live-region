<script>
import Fields from './components/Fields.vue'
import Output from './components/Output.vue'
import LiveRegion from './components/LiveRegion.vue'

export default {
  name: 'app',
  components: {
    Fields,
    Output,
    LiveRegion
  }
}
</script>

<template>
  <main>
    <h1>Live Area</h1>
    <h2>Input</h2>
    <Fields />
    <h2>Output</h2>
    <Output />
    <h2>Example</h2>
    <LiveRegion />
  </main>
</template>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
}

:root {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  margin: 0;
}

main {
  margin: auto;
  padding: 1rem;
  max-width: 42rem;
}
</style>
