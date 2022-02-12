<script setup lang="ts">
defineProps<{
  text: string,
  onclick: Function
}>()
</script>

<template>
  <button type="button" @click="onclick()">{{ text }}</button>
</template>

<style>

</style>
