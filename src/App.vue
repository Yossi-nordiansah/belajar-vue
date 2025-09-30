<script setup>
import CompositionComponent from './components/CompositionComponent.vue'
import Description from './components/Description.vue'
import OptionComponent from './components/OptionComponent.vue'
</script>

<template>
  <Header />
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
  <CompositionComponent />
  <OptionComponent />
  <Description />
</template>

<style scoped></style>
