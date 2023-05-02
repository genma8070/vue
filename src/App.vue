<script setup>
import Card from "./files/Card.vue"
import HeaderView from "./files/HeaderView.vue"
import FooterView from "./files/FooterView.vue"
import Bg from "./files/Bg.vue"
</script>

<template>  

<div class="container">
  <HeaderView />
  <Bg />
  <FooterView />

</div>
</template>

<style scoped>
.container{
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  
}
</style>