<template>
<div class="w-full bg-primary px-12 flex flex-col md:flex-row md:px-20">
  <div class="pt-16 md:pt-24">
    <p class="hero__sub-text font-bold text-xs space-x-0.5">YOUR SMART BANKING IS HERE</p>
    <h2 class="text-white font-extrabold text-5xl mt-2 md:w-2/3 md:leading-tight">Smart banking for your transactions.</h2>
    <p class="hero__sub-header text-lg mt-4">For ambitious companies around the world, Wallet makes moving money as simple.</p>
    <div class="w-full h-16 py-2 px-2 mt-4 bg-input rounded-lg border-gray-700 border shadow-md flex gap-4">
      <input type="text" class="h-full bg-transparent outline-none pl-4 w-3/5 text-white" placeholder="Your email address"  />
      <button class="bg-green-600 hover:bg-green-800 h-full w-2/5 rounded-lg text-white"> Get Started</button>
    </div>
    <div class="w-full flex justify-between gap-4 mt-12">
      <div class="h-14 w-full bg-gray-700 flex justify-center items-center rounded-lg">
        <img src="/img/get-google-play.png" alt="google-play" class=" h-3/4 w-3/4 object-contain" />
      </div>
      <div class="h-14 w-full bg-gray-700 flex justify-center items-center rounded-lg">
        <img src="/img/get-apple-store.png" alt="apple-store" class=" h-3/4 w-3/4 object-contain" />
      </div>
    </div>
  </div>
  <div class="w-full mt-8 md:mt-0 md:flex md:justify-end">
    <img src="/img/phone.png" alt="hero-phone" />
  </div>
</div>
</template>

<style scoped>
.hero__sub-text{
  color: #FEC336;
}

.hero__sub-header{
  color: #DADBDD;
}

.bg-input{
  background: #282828;
  color: #747474;
}
</style>