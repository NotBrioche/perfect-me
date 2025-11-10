<script setup lang="ts">
defineProps(['text'])
</script>

<template>
  <div
    class="hover:cursor-pointer bg-green-700 hover:bg-green-600 rounded-lg p-2 font-bold select-none active:bg-green-500"
  >
    {{ text }}
  </div>
</template>
