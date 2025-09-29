<script setup>
const name = 'Yossi Nordiansah'
const showName = () => console.log(name)
</script>

<template>
  <button @click="showName" class="bg-blue-900 text-white">Show Name</button>
  <h1 class="text-4xl text-green-600">{{ name }}</h1>
</template>
