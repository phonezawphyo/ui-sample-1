<template>
  <button class="button">
    Text: {{ text }}
  </button>
</template>

<script setup lang="ts">
import { defineProps } from 'vue';

type Props = {
  text: string;
}

defineProps<Props>();
</script>
