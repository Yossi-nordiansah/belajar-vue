<script setup>
const name = 'Yossi Nordiansah'
const showName = () => console.log(name)
const buttonAttr = {
  disabled: true,
  class: 'bg-blue-900 text-white rounded ml-4 text-xl font-bold px-2',
}
</script>

<template>
  <button v-bind="buttonAttr" @click="showName">
    {{ buttonAttr.disabled ? 'Loading' : 'Show Name' }}
  </button>
  <h1 class="text-4xl text-green-600">{{ name }}</h1>
</template>
