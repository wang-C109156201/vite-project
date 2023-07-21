<script setup>
  import { ref } from 'vue'
  const count = ref(0)
  const view = ref(0)
  const changeview =(index) =>{
    view.value=index
  }
</script>

<template>
  <div >
    
    <button @click="changeview(0)" class="switch">漢堡</button>
    <button @click="changeview(1)" class="switch">薯條</button>
    <div class="col" v-if="view===0">
      <div class="row top-1 " >
        <img src="../../public/img/卡胡娜大漢堡.jpg" class="img" alt="">
        <div class="introduction">
          <p>卡胡娜大漢堡</p>
          <p>$199</p>
        </div>
        <button @click="count++" class="btn">+</button> 
      </div>
      <div class="row">
        <img src="../../public/img/龍漢堡.jpg" class="img" alt="">
        <div class="introduction">
          <p>龍漢堡</p>
          <p>$299</p>
        </div>
        <button @click="count++" class="btn">+</button>
      </div>
    </div>

    <div class="col" v-if="view===1">
      <div class="row" >
        <img src="../../public/img/小薯.jpg" class="img" alt="">
        <div class="introduction">
          <p>小薯</p>
          <p>$45</p>
        </div>
        <button @click="count++" class="btn">+</button>         
      </div>
      <div class="row">
        <img src="../../public/img/中薯.jpg" class="img" alt="">
        <div class="introduction">
          <p>中薯</p>
          <p>$55</p>
        </div>
        <button @click="count++" class="btn">+</button>
      </div>
    </div>
   <div>
    <p>購物車總數:{{count}}</p>
   </div>

    
  </div>


</template>

<style scoped>
  
  .img{
    width: 100px;
    height: 100px;
    border-radius: 10px;
    margin: 10px;
  }
  .col{
    display: flex;
    flex-direction: column;
  }
  .row{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
  }
  .btn{
   width: 50px; 
   height: 50px;
   border-radius:50%;
   
  }
  .introduction{
    text-align: left;
    width: 150px;
    margin: 20px;
  }
  .switch{
    margin: 10px;
    font-weight: bold;
  }
</style>

