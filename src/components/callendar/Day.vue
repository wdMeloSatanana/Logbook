<script setup lang="ts">
const props = defineProps<{ title: string }>();
</script>

<template>
  <div :class="$style.container">{{ props.title }}</div>
</template>

<style module lang="scss" scoped>
.container {
  height: 10rem;
  width: 10rem;
  background-color: slategrey;
  color: white;
  border-radius: 10%;
  text-align: center;
}
</style>
