<template>
    <div class=" fixed z-20 top-0 bg-gradient-to-b px-8 mb-8 from-black h-20 md:h-28  flex items-center w-full">
        <button id="menubtn" type="button" v-on:click="toggle()">
            <svg viewBox="0 10 100 50" width="30" height="30" class=" fill-white md:hidden float-left relative">
                <rect width="80" height="12"></rect>
                <rect y="30" width="80" height="12"></rect>
                <rect y="60" width="80" height="12"></rect>
            </svg>
        </button>
        <img src="https://ocard.co//assets/ofb/image/logo.e7d1e7caec40820bfb17ee7a1fd87fee.svg" alt="" class="w-28">
        <div class="flex">
            <ul class="px-10 hidden md:flex">
                <a href="#" class=" px-6">服務介紹</a>
                <a href="#" class=" px-6">部落格</a>
                <a href="#" class=" px-6">價格方案</a>
            </ul>
            <a href="#" class=" px-6">立即諮詢</a>
        </div>
        <!-- <p class=" text-right">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut dolore s</p> -->
        <div 
            id="menu"
            class=" fixed z-10 top-20 h-10 md:hidden flex justify-center w-full"
            v-if="showDiv"
        >
            <a href="#" class=" px-6">服務介紹</a>
            <a href="#" class=" px-6">部落格</a>
            <a href="#" class=" px-6">價格方案</a>
        </div>
    </div>

</template>

<script>
    export default {
        // name:"",
        methods: {
            toggle() {
                this.showDiv = !this.showDiv;
                console.log("點擊了按鈕"); // 在這裡加入 console.log 語句
            },
        },
        data: function () {
            return {
                showDiv: false,
            };
        },
        // methods:{
        //     toggle(){
        //         console.log("hi");
        //         console.log(this.showDiv);
        //         this.showDiv = !this.showDiv;
        //         console.log(this.showDiv);
        //         this.toggle("menu",hidden)
        //     },
        //     show(){
        //         console.log("click");
        //     }
        // },
        // data: function () {
            
        //     return {
        //         showDiv: false,
        //     }
        // },
    }
</script>