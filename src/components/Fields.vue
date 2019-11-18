<script>
export default {
  name: 'Fields',
  props: {}
}
</script>

<template>
  <fieldset>
    <legend>Live Region</legend>
    <p>
      <label for="role">role: </label>
      <select id="role">
        <option selected>status</option>
        <option>alert</option>
        <option>log</option>
        <option>marquee</option>
      </select>
    </p>
    <p>
      <label for="aria-live">aria-live value: </label>
      <select id="aria-live">
        <option selected>polite</option>
        <option>assertive</option>
        <option>rude</option>
        <option>off</option>
      </select>
    </p>
    <p>
      <label for="aria-atomic">aria-atomic value: </label>
      <select id="aria-atomic">
        <option selected>true</option>
        <option>false</option>
      </select>
    </p>
    <p>
      <label for="aria-relevant">aria-relevant value: </label>
      <select id="aria-relevant">
        <option selected>text</option>
        <option>additions</option>
        <option>removals</option>
        <option>all</option>
      </select>
    </p>
    <p>
      <label for="text">text: </label>
      <textarea id="text"></textarea>
    </p>
  </fieldset>
</template>

<style scoped>
  fieldset {
    display: block;
    padding: 1rem;
    border: 1px solid currentColor;
  }
  textarea {
    appearance: none;
    display: block;
    padding: 1rem;
    width: 100%;
    max-width: 100%;
    border: 1px solid currentColor;
  }
</style>
