<script lang="ts" setup>
const props = defineProps({
  label: String,
  link: String,
});
</script>

<template>
  <a target="_blank" :href="props.link" class="btn" role="button" >
    {{ props.label }}
  </a>
</template>

<style scoped>
.btn {
  color: #0b0014;
  background-color: #f5e9e2;
  display: inline-block;
  width: 20rem;
  padding:1.75rem 0rem;
  font-size: xx-large;
  text-decoration: none;
  border: 0;
  border-radius: 4px;
  text-align: center;
}

.btn:hover {
  transform:scale(1.1,1.1);
}
</style>