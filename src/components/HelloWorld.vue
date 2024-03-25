<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
  <div>
    <p class="color-message">{{ msg }}</p>
  </div>
</template>

<style scoped>

.color-message {
  max-width: 600px;
}

</style>

