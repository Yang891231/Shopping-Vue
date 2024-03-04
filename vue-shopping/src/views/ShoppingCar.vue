<template>
  <div>
    <h1 class="text-3xl p-2 font-bold ml-5">購物車確認</h1>
    <div class="grid grid-cols-6 text-xl border-t-2 border-b-2 pt-2 pb-2 w-11/12 mx-auto">
      <span></span>
      <span class="text-center">商品圖片</span>
      <span class="text-center">商品名稱</span>
      <span class="text-center">價錢</span>
      <span></span>
    </div>
    <div class="grid grid-cols-6 text-xl border-t-2 border-b-2 pt-2 pb-2 w-11/12 mx-auto">
      <input type="checkbox" name="" id="" class="w-8 ml-20">
      <img src="@/assets/300x300.png" alt="" class="w-52 ml-8">
      <span class="text-center mt-20">商品名稱</span>
      <span class="text-center mt-20">價錢</span>
      <button class="border w-20 h-12 mt-16 ml-16 p-2 hover:bg-slate-500">刪除</button>
    </div>
    <div class="flex justify-start flex-col items-end">
      <h1 class="text-3xl font-bold mr-10">商品數量:</h1>
      <h1 class="text-3xl font-bold mr-10">商品總金額:</h1>
    </div>
    <div class="flex justify-between mt-5 text-xl">
      <button class="p-2 bg-orange-950 rounded-lg ml-16 text-white">回上頁繼續購買</button>
      <button class="p-2 bg-purple-900 rounded-lg mr-16 text-white">確認購買</button>
    </div>

  </div>
</template>

