<template>
  <NuxtWelcome />
  <h1>Current color: {{ color }}</h1>
</template>

<script setup lang="ts">
const state = ref('blue');
const color = state // Same as useState('color')
</script>
