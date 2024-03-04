<template>
    <div>
        <h1 class="text-3xl p-2 font-bold ml-5">購物車確認</h1>
        <div class="grid grid-cols-4 text-xl border-t-2 border-b-2 pt-2 pb-2 w-11/12 mx-auto">
            <span class="text-center">商品圖片</span>
            <span class="text-center">商品名稱</span>
            <span class="text-center">價錢</span>
            <span class="text-center">數量</span>
        </div>
        <div class="grid grid-cols-4 text-xl border-b-2 pt-2 pb-2 w-11/12 mx-auto">
            <img src="@/assets/300x300.png" alt="" class="w-52 ml-28">
            <span class="text-center mt-24">商品名稱</span>
            <span class="text-center mt-24">價錢</span>
            <span class="text-center mt-24">數量</span>
        </div>
        <div class="grid grid-cols-6 text-xl border-t-2 border-b-2 pt-2 pb-2 w-11/12 mx-auto mt-8">
            <span class="text-center">姓名</span>
            <span class="text-center">電話</span>
            <span class="text-center">地址</span>
            <span class="text-center">付款方式</span>
            <span class="text-center">電子信箱</span>
            <span class="text-center">運送方式</span>
        </div>
        
        <div class="flex justify-between mt-5 text-xl ">
            <button class="w-full p-2 bg-purple-900 rounded-lg  text-white">回首頁</button>
        </div>

    </div>
</template>
