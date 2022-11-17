<template>
  <div class="bar"></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({});
</script>

<style lang="scss">
@import '@/styles/foo';
@import 'styles/bar';

.bar {
  background-color: $c;
}
</style>
