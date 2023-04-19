<template>
  <div class="container">
    <h1>{{ props.msg }}</h1>
  </div>
</template>

<script setup lang="ts">

const props = defineProps({
    msg: { type: String, required: true }
})

</script>

<style scoped lang="sass">

</style>
