<script setup lang="ts">
const props = defineProps({
  class: {
    type: String,
  },
})
</script>

<template>
  <div class="slidev-layout better-center h-full flex flex-col">
  <div class="text-center w-full">
    <slot />
  </div>
  <div class="place-self-center my-auto example" :class="props.class">
    <slot name="example" />
  </div>
  <div class="place-self-center">
  <slot name="task" />
  </div>
  </div>
</template>
