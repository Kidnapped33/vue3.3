<script setup lang="ts">
import { ref } from 'vue'
import type { User } from './types';

// defineProps<User>()

const count = ref(0)
</script>

<template>
   <!-- <div>{{ $props?.userName }}</div> -->
   <!-- <div>{{ $props?.userAge }}</div> -->
  {{ count }}
</template>

<style scoped>
</style>
