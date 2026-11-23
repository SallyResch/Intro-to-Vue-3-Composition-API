<script setup>
import { ref } from 'vue'
import greenSockImage from './assets/images/socks_green.jpeg'
import blueSockImage from './assets/images/socks_blue.jpeg'
const product = ref('Socks')
//Change ref of image to change picture between blue and green
const image =ref(blueSockImage)
</script>

<template>
  <div class="product-display">
    <div class="product-container">
      <div class="product-image">
       <img :src="image" alt="">
      </div>
      <div class="product-info">
        <h1>{{ product }}</h1>
      </div>
    </div>
  </div>
</template>