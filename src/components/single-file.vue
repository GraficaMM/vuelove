<script setup lang="ts">
import { ref } from 'vue'

const saludo = ref('hola a todos')
</script>

<template>
  <div>
    {{ saludo }}
  </div>
</template>

<style scoped></style>
