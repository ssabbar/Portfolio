<template>
  <div class="p-2 float-left">
    <div class="p-5 float-left flex flex-col items-center">
      <img :src="`/images/${fileName}`" class="icon-image" />
      <span class="mt-2">{{ text }}</span>
    </div>
  </div>
</template>

<script setup>
const props = defineProps(["fileName", "text"]);
</script>

<style scoped>
.icon-image {
  width: 3em; /* Larger size as requested */
  height: 3em; /* Larger size as requested */
  margin-bottom: 0.5em; /* Space between image and text */
}
</style>