<template>
  <div>
    <h1>Test {{ name }}</h1>
  </div>
</template>

<script setup lang="ts">
defineProps<{
  name: string;
}>();
</script>
