<template>
  <div>
    <WithRefAndWithSlot ref="aaaRef"></WithRefAndWithSlot>
  </div>
</template>
<script setup lang="ts">

const aaaRef = ref<ComponentInstance['WithRefAndWithSlot']>()
</script>
