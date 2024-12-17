<script setup lang="ts">
</script>

<template>
  <van-calendar :poppable="false" :show-confirm="false" :min-date="new Date(2025, 2, 1)"
    :max-date="new Date(2025, 3, 31)" type="range" :default-date="[new Date(2025, 2, 15), new Date(2025, 3, 3)]" />
</template>
