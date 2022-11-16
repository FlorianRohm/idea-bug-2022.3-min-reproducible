<template>
  <TestComponent></TestComponent>
</template>

<script setup lang="ts">
import TestComponent from '@/testComponent.vue';</script>

<style lang="scss">
@import '@/styles/foo';

.bar {
  background-color: $c;
}
</style>
