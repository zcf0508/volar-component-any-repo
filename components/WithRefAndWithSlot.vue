<template>
  <div>
    <ATree ref="treeRef"></ATree>
    <slot></slot>
  </div>
</template>

<script setup lang="ts">
const treeRef = ref<ComponentInstance['ATree']>()

</script>

<style scoped>

</style>
