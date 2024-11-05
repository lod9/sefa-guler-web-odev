<script setup>
import { ref } from 'vue'


</script>

<template>
  <div class="w-full h-[50px] flex justify-center items-center gap-x-[253px]">
    <div class="w-[200px] h-full flex gap-x-[20px] items-center ">
      <img src="../assets/logo.svg"  class="w-10 h-10" />
      <p class="whitespace-nowrap w-[31.394px] font-[Montserrat] font-bold text-black">Sefa Host</p>
    </div>
    <ul class="w-fit h-fit flex gap-x-[66px]  flex items-center">
        <li class="cursor-pointer flex items-center text-[13px] font-[Montserrat] text-black font-semibold w-fit p-[10px] gap-x-[8px]">Web Barındırma 
          <img src="../assets/dropdown.svg" class="w-[24px] h-[24px]" />
        </li>
        <li class="cursor-pointer flex items-center text-[13px] font-[Montserrat] text-black font-semibold w-fit p-[10px] gap-x-[8px]">Web Koruma 
          <img src="../assets/dropdown.svg" class="w-[24px] h-[24px]" />
        </li>
        <li class="cursor-pointer flex items-center text-[13px] font-[Montserrat] text-black font-semibold w-fit p-[10px] gap-x-[8px]">Domain 
          <img src="../assets/dropdown.svg" class="w-[24px] h-[24px]" />
        </li>
        <li class="cursor-pointer flex items-center text-[13px] font-[Montserrat] text-black font-semibold w-fit p-[10px] gap-x-[8px]">SSL 
          <img src="../assets/dropdown.svg" class="w-[24px] h-[24px]" />
        </li>
    </ul>
    <div class="flex justify-center items-center text-[12px] w-fit h-[45px] p-[10px] bg-black rounded-lg font-[Montserrat] font-normal ">Yapay Zeka</div>
    
  </div>
</template>

<style scoped>

</style>
