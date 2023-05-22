<script setup lang="ts">
// import type { User } from './types';
import type { UserInfo } from "../global";
import type { User } from "./types";

// const xxx = defineProps<UserInfo>();
defineProps<UserInfo & User>();

</script>

<template>
  <div>{{ $props?.userName }}</div>
  <div>{{ $props?.userAge }}</div>
</template>

<style scoped></style>
