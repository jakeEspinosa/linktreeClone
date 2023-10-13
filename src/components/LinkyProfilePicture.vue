<script lang="ts" setup>
const props = defineProps({
  imageUrl: String,
});
</script>

<template>
  <img :src="props.imageUrl" />
</template>

<style scoped>
img {
  width: 10rem;
  height: 10rem;
  border-radius: 100%;
  filter: drop-shadow(0 0 0.25rem #E5EAF5);
}
</style>