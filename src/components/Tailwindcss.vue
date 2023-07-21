<script setup>
    import  Header  from "../components/Header.vue";
</script>


<template >
    <body class=" bg-black" > 
        <div class="bg-black text-white font-bold w-full">
            <Header></Header>
            <div class=" relative w-full">
                <div class=" bg-black w-full h-20 md:h-24"></div>
                <img src="../../public/img/HomePage-1.jpg" alt="Homepage_img" class="hidden md:flex md:z-0 md:w-full md:h-[calc(100vh-6rem)] md:relative md:rounded-2xl" >
                <img src="../../public/img/HomePage-3.jpg" alt="Homepage_img" class="z-0 w-full h-[calc(100vh-5rem)] md:hidden relative rounded-2xl" >
                <div class=" z-0 absolute flex flex-col justify-center items-center w-full inset-0">
                    <p class=" text-5xl md:text-7xl ">會員系統</p>
                    <p class=" text-xl md:text-2xl">輕鬆制定品牌專屬會員計劃</p>
                    <p class="text-xl md:text-2xl">經營顧客更容易</p>
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 -960 960 960" class="animate-bounce w-6 h-6 fill-white z-10">
                        <path d="M450-800v526L202-522l-42 42 320 320 320-320-42-42-248 248v-526h-60Z"/>
                    </svg>

                </div>
            </div>
            
            <nav class="">
                <!-- <img src="../../public/img/HomePage-1.jpg" alt=""> -->
                
                <div>
                    <p class=" font-bold text-center text-3xl md:text-4xl m-10">會員卡數位化，輕鬆鎖定 VIP 客群</p>
                    <div class=" w-auto m-5 md:flex">
                        <div class=" bg-[#222222] p-10 w-full md:w-1/2 md:mx-2 my-4 rounded-xl">
                            <p class=" text-2xl">無須發售實體會員卡</p>
                            <p class=" text-white text-opacity-50">顧客可在 LINE、Messenger、Ocard APP 開啟電子會員卡查看點數、優惠券資訊</p>
                        </div>
                        <div class=" bg-[#222222] p-10  w-full md:w-1/2  md:mx-2 my-4 rounded-xl">
                            <p class=" text-2xl">自動蒐集顧客資料</p>
                            <p class=" text-white text-opacity-50">可根據顧客消費輪廓及特性自動上標，企業可針對擁有特定標籤的客群做數據分析及再行銷</p>
                        </div>
                    </div>
                    <div class=" md:flex w-auto m-5 ">
                        <div class=" bg-[#222222] p-10 w-full md:w-1/2 md:mx-2 my-4 rounded-xl">
                            <p class=" text-2xl">自動分眾貼標籤</p>
                            <p class=" text-white text-opacity-50">顧客可在 LINE、Messenger、Ocard APP 開啟電子會員卡查看點數、優惠券資訊</p>
                        </div>
                        <div class=" bg-[#222222] p-10 w-full md:w-1/2 md:mx-2 my-4 rounded-xl">
                            <p class=" text-2xl">會員分級制度</p>
                            <p class=" text-white text-opacity-50">可自訂各級別 VIP 升級門檻、可獲取的優惠，給予 VIP 尊榮優惠</p>
                        </div>
                    </div>
                </div>
                <div class=" md:flex items-center m-20">
                    <img src="../../public/img/c-card.jpg" alt="" class=" w-1/2">
                    <div class="content-center justify-center text-center mt-10">
                        傳統會員卡VS電子會員卡
                    </div>
                </div>
                <div class=" md:flex items-center w-full" >
                    <div class="md:w-1/2 p-8" >
                        即時呈現會員數據報表，輕鬆掌握營運狀況
                    </div>
                    <img src="../../public/img/crm-system.jpg" alt="" class="p-8 md:w-1/2 md:m-5">
                </div>
                <div class="bg-[#222222] rounded-2xl w-[calc(100vh-100px)] h-20 m-5 flex items-center justify-center content-center">
                    <p>想用 20% 的行銷成本，換得 80% 的營收？</p>
                    <button>立即諮詢專業顧問</button>
                </div>
                <div class=" bg-black h-7 w-full"></div>
            </nav>

            <!-- <div class="">
                <div>
                    Ocard CRM 系統
                    會員系統
                    電子集點
                    行銷工具
                    精準再行銷
                    多元串接69
                </div>
                <div>
                    Ocard 線上點
                    獨家優勢
                    系統功能
                    Ocard Rewards
                    計劃簡介
                    Ocard APP
                    Ocard APP
                </div>
                <div>
                    延伸連結
                    案例介紹
                    部落格
                    品牌資源中心
                    人才招募
                    下載 Ocard
                    票券查驗
                </div>
                <div>
                    星期一至五 10:00～18:30
                    (02)7751-5407
                    service@ocard.co
                </div>
            </div> -->
        
        </div>

    </body>
    


</template>

<style scoped>

</style>