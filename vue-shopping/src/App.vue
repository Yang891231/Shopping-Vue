<script>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <nav class="flex justify-between h-16 items-center p-5 bg-gray-700 text-white">
    <div class="flex gap-3">
      <!-- <RouterLink to="/" class="p-3">Home</RouterLink> -->
      <RouterLink to="/" >Shopping</RouterLink>
      <RouterLink to="/ShoppingCheck" >ShoppingCheck</RouterLink>
      <RouterLink to="/buySuccess" >BuySuccess</RouterLink>
    </div>
    <div class="mr-4">
      <span class="float-end relative top-5 bg-red-600 h-7 w-7 rounded-full flex items-center
      justify-center left-4">0</span>
      <RouterLink to="/ShoppingCar">
        <img src="./assets/326700_cart_shopping_icon.png" class="h-8">
      </RouterLink>
      
    </div>
  </nav>
  <RouterView/>
</template>

<style scoped>
nav {
  width: 100%;
  font-size: 24px;
  text-align: center;
}

</style>
