
<!-- 
<template>
    <div class="item">
        <a href="#" @click="toTaobao">淘宝</a>
    </div>
  </template> -->




<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(()=>{
    toTaobao()
}
)

const url= 'https://item.taobao.com/item.htm?ali_refid=a3_430582_1006:1124607654:N:jrj8Esb7uucRJXUClzGBx7i5seCDif1O:c1786202f1f1dc37be1a08d390199a28&ali_trackid=162_c1786202f1f1dc37be1a08d390199a28&id=751657755234&spm=a21n57.1.0.0&skuId=5351143622307'

const testherf= 'https://t.asczwa.com/taobao?backurl='
const schemeurl ='taobao://detail.tmall.com/item.htm?id=632351705697'

function toTaobao(){
    location.href=schemeurl
}


</script>

<!-- https://main.m.taobao.com/security-h5-detail/home?id=632351705697 -->