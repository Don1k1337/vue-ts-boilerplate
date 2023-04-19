<template>
  <div class="container">
      <TestComponent :msg="testMsg" />
  </div>
</template>

<script setup lang="ts">
import TestComponent from "./components/TestComponent.vue";

const testMsg = 'Test msg'
</script>

<style scoped lang="sass">
.container
  text-align: center
</style>
