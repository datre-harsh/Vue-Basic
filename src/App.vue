<template>
  <BaseLayout>
    <template #header>
      <h1>Here may be a page title.</h1>
    </template>
    <template #main>
      <p>A paragraph of the main content.</p>
      <p>Another one</p>
    </template>
    <template #footer>
      <p>Here's contact info.</p>
    </template>
  </BaseLayout>
</template>

<script setup>
import BaseLayout from './BaseLayout.vue'
</script>

<style lang="scss" scoped></style>