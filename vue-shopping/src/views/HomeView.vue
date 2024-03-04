<script>

</script>

<template>
    <div class="w-full px-6 text-3xl pt-2">
        <div>
            <h1 class="font-bold">商品列表</h1>
        </div>
        <div class="flex justify-end">
            <img src="@/assets/iconl_0.png" alt="" class="w-12">
            <img src="@/assets/iconr_0.png" alt="" class="w-12">
        </div>
        <div class="flex gap-3 flex-wrap justify-center text-xl mt-2">
            <div class="w-1/6 border rounded-lg flex flex-col">
                <img src="../assets/300x300.png" alt="">
                <div class="w-full h-72 ml-2">
                    <h2 class="mt-2">XXX</h2><br>
                    <p>XXX</p><br>
                    <p>價格 : XXX</p>
                </div>
                <div>
                    <p class="ml-2">
                        數量 : <button class="border rounded-lg w-10 text-xl">-</button>
                        <input type="number" min="1" class="text-center w-12">
                        <button class="border rounded-lg w-10 text-xl">+</button>
                    </p>
                </div>
                <div class="flex bg-purple-400 justify-center items-center mt-2 pt-1 pb-1 ">
                    <img src="../assets/326700_cart_shopping_icon.png" class="h-5 w-5">
                    <button>加入購物車</button>
                </div>
            </div>
        </div>
        <div class="grid">
            <div class="grid grid-cols-5 mb-3 border-t-2 mt-3 pt-2">
                <span class="text-center">商品圖片</span>
                <span class="text-center">商品名稱</span>
                <span class="text-center">商品描述</span>
                <span class="text-center">價錢</span>
            </div>
            <div>
                <div class="grid">
                    <div class=" border rounded-lg grid-cols-5 grid">
                        <img src="@/assets/300x300.png" alt="" class="ml-9">
                        <div class="w-full h-60">
                            <h2 class="text-center mt-32">XXX</h2><br>
                        </div>
                        <p class="text-center flex items-center">XXX</p>
                        <p class="text-center mt-32">$XXX</p>
                        <div>
                            <p class="text-center mt-24">
                                數量 : <button class="border rounded-lg w-10 text-xl">-</button>
                                <input type="number" min="1" value="1" class="text-center w-12">
                                <button class="border rounded-lg w-10 text-xl">+</button>
                            </p>
                            <div class="flex bg-purple-400 justify-center items-center mx-auto mt-2 w-56 rounded-lg">
                                <img src="@/assets/326700_cart_shopping_icon.png" class="h-5 w-5">
                                <button>加入購物車</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.change {
    @apply bg-orange-200
}
</style>