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
  width: 10rem;
  height: 1.75rem;
  color: white;

  &:hover {
    background: lightgray;
    color: black;
    cursor: pointer;
  }
}
</style>
