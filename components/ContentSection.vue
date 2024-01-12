<template>
  <div>
    <div class="sticky top-0 z-10">
      <DesignedIcon :name="name" :text="text" />
    </div>
    <slot></slot>
  </div>
</template>


<script setup>
const props = defineProps({
  name: String,
  text: String,
});
</script>
