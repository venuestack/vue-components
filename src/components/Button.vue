
<script setup lang="ts">
  import { defineProps } from 'vue';

  defineProps<{
    text: string;
  }>();
</script>

<template>
  <button class="px-6 py-2 bg-slate-950 text-white hover:bg-slate-800 rounded-md">{{ text }}</button>
</template>