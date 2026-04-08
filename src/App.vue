<script setup lang="ts">
import ProgressBar from './components/ProgressBar.vue'
import SectionContent from './components/SectionContent.vue'
</script>

<template>
  <main>
    <ProgressBar />
    <SectionContent />
  </main>
</template>

<style scoped>
main {
  position: relative;
  max-width: 1280px;
  height: 100%;
  width: 100%;
  padding: 24px;
}
</style>
