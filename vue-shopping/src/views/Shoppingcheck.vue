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
        <div class="grid grid-cols-6 text-xl border-b-2 pt-2 pb-2 w-11/12 mx-auto">
            <span></span>
            <img src="@/assets/300x300.png" alt="" class="w-52 ml-10">
            <span class="text-center mt-24">商品名稱</span>
            <span class="text-center mt-24">價錢</span>
            <span></span>
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">姓名</h1>
            <input type="text" class="border-2 p-2">
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">電話</h1>
            <input type="text" class="border-2 p-2">
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">地址</h1>
            <input type="text" class="border-2 p-2">
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">電子信箱</h1>
            <input type="email" class="border-2 p-2">
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">付款方式</h1>
            <div class="flex gap-3 text-lg">
                <div class="ml-3">
                    <input type="radio" value="信用卡" id="payStyle1" name="payStyle" required>
                    <label for="payStyle1">信用卡</label>
                </div>
                <div>
                    <input type="radio" value="貨到付款" id="payStyle2" name="payStyle" required>
                    <label for="payStyle2">貨到付款</label>
                </div>
            </div>
        </div>
        <div class="w-11/12 flex flex-col mx-auto mt-5">
            <h1 class="text-xl p-2 font-bold ">運送方式</h1>
            <div class="flex gap-3 text-lg">
                <div class="ml-3">
                    <input type="radio" value="宅配" id="transportStyle1" name="transportStyle" required>
                    <label for="transportStyle1">宅配</label>
                </div>
                <div>
                    <input type="radio" value="超商取貨" id="transportStyle2" name="transportStyle" required>
                    <label for="transportStyle2">超商取貨</label>
                </div>
            </div>
        </div>

        <div class="flex justify-start flex-col items-end">
            <h1 class="text-3xl font-bold mr-10">商品數量:</h1>
            <h1 class="text-3xl font-bold mr-10">商品總金額:</h1>
        </div>
        <div class="flex justify-between mt-5 text-xl">
            <button class="p-2 bg-orange-950 rounded-lg ml-16 text-white">回上頁繼續加購</button>
            <button class="p-2 bg-purple-900 rounded-lg mr-16 text-white">確認送出</button>
        </div>

    </div>
</template>

