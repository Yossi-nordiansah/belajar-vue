<script setup>
const text =
  '<h1 class="text-4xl font-bold">ini merupakan sebuah deskripsi</h1><br><p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequuntur sapiente cupiditate suscipit iure aut dolorum omnis aspernatur doloremque atque magni, saepe harum dolores ducimus? Dolorum voluptatem deleniti laudantium eum sint.</p>'

const productId = 4
const style = 'text-violet-500 text-4xl font-bold'
</script>

<template>
  <div v-html="text" class="mt-14"></div>
  <p :id="productId" :class="style">Hello World</p>
</template>
