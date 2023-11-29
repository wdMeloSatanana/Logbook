<script setup lang="ts">
defineProps<{
  txt: string;
}>();
</script>

<template>
  <button :class="$style.btn">{{ txt }}</button>
</template>

<style module lang="scss" scoped>
.btn {
  background: slategray;
  border: none;
  width: 92%;
  height: 2rem;
  color: white;
  margin: 0.1rem;
  border-radius: 5%;
  border-bottom: 0.25rem rgb(90, 103, 116);
  &:hover {
    background: lightgray;
    color: black;
    cursor: pointer;
  }
}
</style>
