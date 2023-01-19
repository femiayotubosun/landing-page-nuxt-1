<script lang="ts">
  export default {
    methods: {
      toggleSidebar(){
        document.querySelector('#jsSidebar')!.classList.toggle("hidden")
      }
    }
  }
</script>
<template>
  <div class="w-full py-4 px-2 md:px-12 flex justify-evenly items-center bg-primary font-family-primary">
    <div class="w-8 h-8 bg-white md:hidden" @click="toggleSidebar"></div>
    <div class="h-96 w-80 absolute bg-white left-2 top-4 md:hidden hidden flex flex-col items-end" id="jsSidebar">
      <div class="h-8 w-8 bg-primary" @click="toggleSidebar"></div>
    </div>
    <div class="text-white font-bold text-2xl w-2/5 cursor-pointer leading-relaxed"> Smart B</div>
    <nav class=" hidden md:flex justify-between align-middle text-xs text-gray-400 leading-normal w-1/5">
        <a href="#home" class="hover:text-white" style="line-height: 30px">Home</a>
      <a href="#product" class="hover:text-white" style="line-height: 30px">Product</a>
      <a href="#pricing" class="hover:text-white" style="line-height: 30px">Pricing</a>
    </nav>
    <div class="flex gap-6 w-2/6  justify-end">
      <button class="text-gray-400 text-xs hover:text-white">Login</button>
      <button class="bg-green-600 hover:bg-green-800 text-white rounded-sm p-3 font-bold text-xs">Sign up</button>
    </div>
  </div>
</template>
