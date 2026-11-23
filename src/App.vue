<script setup>
import {ref} from "vue"
const product = ref("Socks")
const description = ref("They are warm and cozy and can be utelized any time of the day to keep your feet nice and happy")
</script>

<template>
  <div class="product-display">
    <div class="product-container">
      <div class="product-info">
        <h1>{{ product }}</h1>
        <p>{{ description }}</p>
      </div>
    </div>
  </div>
</template>