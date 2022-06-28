<script setup>
const { x, y } = useMouse();
</script>

<template>
  <code> Mouse position is at: {{ x }}, {{ y }} </code>
</template>