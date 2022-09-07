<template>
  <NuxtWelcome />
  <h1>Current color: {{ color }}</h1>
</template>

<script setup>
const color = useState('color') // Same as useState('color')
</script>
