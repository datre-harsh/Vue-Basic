<template>
  <div style="background-color: lightgreen; padding: 5px">
    Child component.
    <ComponentB></ComponentB>
    <ComponentB></ComponentB>
    <ComponentB></ComponentB>
  </div>
</template>

<script setup>
import ComponentB from './ComponentB.vue'
</script>

<style scoped></style>