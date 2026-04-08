<script setup lang="ts">
// import DocumentationIcon from './icons/IconDocumentation.vue'
</script>

<template>
  <!-- <DocumentationIcon /> -->
  <div class='progress-bar'>
  </div>
</template>

<style scoped>
.progress-bar {
  position: absolute;
  left: 24px;
  top: 24px;
  bottom: 24px;
  border: 2px solid black;
  border-radius: 12px;
  width: 24px;
}

@media (min-width: 800px) {
  .progress-bar {
    position: absolute;
    right: 24px;
    top: 24px;
    border: 2px solid black;
    border-radius: 12px;
    height: 24px;
    width: auto;
    bottom: auto;
  }
}
</style>
