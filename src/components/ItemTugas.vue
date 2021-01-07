<template>
  <div class="form-check">
    <input
      onclick=""
      class="form-check-input"
      type="checkbox"
      value=""
      id="defaultCheck1"
    />
    <label
      v-bind:class="{ 'item-completed': tugasSaya.isDone }"
      class="form-check-label item"
      for="defaultCheck1"
    >
      {{ tugasSaya.namaTugas }}
    </label>
  </div>
</template>

<script>
export default {
  name: "ItemTugas",
  props: ["tugasSaya"],
};
</script>

<style scoped>
</style>