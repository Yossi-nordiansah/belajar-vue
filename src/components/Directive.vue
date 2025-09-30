<script setup>
const url = {
  attr: 'href',
  link: '/home',
}
</script>

<template>
  <a :[url.attr]="url.link"></a>
</template>
