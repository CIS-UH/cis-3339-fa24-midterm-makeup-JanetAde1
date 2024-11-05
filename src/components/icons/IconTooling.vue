<template>
  <svg :width="width" :height="height" :fill="fillColor">
    <path d="M10 3.22l-.61-.6a5.5 5.5 0 0 0-7.666.105 5.5 5.5 0 0 0-.114 7.665L10 18.78l8.39-8.4a5.5 5.5 0 0 0-.114-7.665 5.5 5.5 0 0 0-7.666-.105l-.61.61z" />
  </svg>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  width: {
    type: Number,
    default: 20
  },
  height: {
    type: Number,
    default: 20
  },
  fillColor: {
    type: String,
    default: 'currentColor'
  }
});
</script>