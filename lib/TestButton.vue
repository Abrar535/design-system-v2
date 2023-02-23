<template>
<button @click="click"> {{ msg }}</button>
</template>

<script setup lang="ts">
defineProps({
      msg: { type: String }
    }
)
function click() {
  alert('Button clicked!!');
}

</script>

<style scoped>

</style>
