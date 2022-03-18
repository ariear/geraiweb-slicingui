<template>
<div class="relative" id="home">
  <div class="font-pupylinux clip pt-52 pb-56 border">
      <div class="text-white w-[96vw] md:w-[620px] text-center mx-auto">
          <p class="font-normal text-4xl md:text-6xl mb-4">Gerai <span class="font-light">Web</span></p>
          <p class="font-light text-lg md:text-2xl mb-6" v-text="quotes"></p>
          <button class="bg-white py-3 px-8 text-[#0099FF] text-base md:text-lg font-light rounded-full">Contact Me</button>
      </div>
  </div>
      <img src="/asset/comp.png" class="absolute left-0 -bottom-10 md:-bottom-28 lg:-bottom-48 right-0 mx-auto w-[80vw] md:w-[500px] lg:w-[600px] xl:w-[700px]" alt="">
</div>
</template>

<script>
export default {
    data() {
        return {
            quotes: 'Website yang bergerak dibidang jasa Digital Marketing, Desain Grafis dan pembuatan Website untuk kebutuhan anda.'
        }
    },
}
</script>

<style>
.clip{
   background: rgb(0,153,255);
background: linear-gradient(180deg, rgba(0,153,255,0.8211659663865546) 23%, rgba(0,194,255,1) 44%);
clip-path: ellipse(71% 59% at 50% 40%);
}
</style>