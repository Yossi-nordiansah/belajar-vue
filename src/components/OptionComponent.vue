<script>
export default {
  data() {
    return {
      name: 'Yossi Nordiansah',
    }
  },
  methods: {
    showName() {
      console.log(this.name)
    },
  },
}
</script>

<template>
  <button @click="showName" class="bg-blue-900 text-white">Show Name</button>
  <h1 class="text-4xl text-green-500">{{ name }}</h1>
</template>
