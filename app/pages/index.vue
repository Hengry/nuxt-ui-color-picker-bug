<script setup lang="ts">
const color = ref('#000000')
</script>

<template>
  <USlideover>
    <UButton>
      test
    </UButton>
    <template #content>
      <UColorPicker v-model="color" />
    </template>
  </USlideover>
</template>
