
<script setup lang="ts">
  import { defineProps } from 'vue';

  defineProps<{
    text: string;
  }>();
</script>

<template>
  <button class="px-6 py-2 bg-black text-white hover:bg-gray-800 rounded-md">{{ text }}</button>
</template>