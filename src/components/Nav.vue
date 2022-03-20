<template>
  <nav class="font-pupylinux text-white fixed flex items-center justify-between container left-0 right-0 mx-auto py-9 z-40 px-6 md:px-8 xl:px-0 anjim transition-all">
      <p class="font-medium text-4xl md:block hidden">Gerai<span class="font-light">Web</span></p>
      <p class="font-medium text-3xl md:hidden block">G<span class="font-light">W.</span></p>
      <div class="hidden md:flex items-center font-normal text-lg">
          <p class="mr-8"><a href="#home">Home</a></p>
          <p class="mr-8"><a href="#pricing">Pricing</a></p>
          <p class="mr-8"><a href="#services">Services</a></p>
          <p><a href="#contact">Contact</a></p>
      </div>
      <!-- mobile menu -->
      <div class="md:hidden">
        <img v-if="!bukamenu" src="/asset/menu-white.png" class="w-[35px] z-40 relative" alt="" @click="bukamenu = !bukamenu">
        <img v-else src="/asset/silang-menu-white.png" class="w-[35px] z-40 relative" alt="" @click="bukamenu = !bukamenu">
        <div class="fixed top-0 right-0 h-screen bg-[#58abe2] z-30 flex flex-col justify-center items-center overflow-hidden transition-all" :class="bukamenu ? 'w-[80vw]' : 'w-0' ">
          <p><a href="#home">Home</a></p>
          <p class="mt-2"><a href="#pricing">pricing</a></p>
          <p class="mt-2"><a href="#services">Services</a></p>
          <p class="mt-2"><a href="#contact">Contact</a></p>
        </div>
      </div>
      <!-- end mobile menu -->
  </nav>
</template>

<script>
export default {
  data() {
    return {
      bukamenu: false
    }
  },
  mounted() {
    const anjim = document.querySelector('.anjim')
    window.addEventListener('scroll', (e) => {
      console.log(window.scrollY);
      if (window.scrollY > 100) {
        anjim.classList.add('pasnavscroll')
        anjim.classList.remove('container')
        anjim.classList.add('py-5')
        anjim.classList.remove('py-9')
        anjim.classList.add('xl:px-16')
        anjim.classList.remove('xl:px-0')
      }else{
        anjim.classList.remove('pasnavscroll')
        anjim.classList.add('container')
        anjim.classList.remove('py-5')
        anjim.classList.add('py-9')
        anjim.classList.remove('xl:px-16')
        anjim.classList.add('xl:px-0')
      }
    })
  },
}
</script>

<style>
.pasnavscroll{
  width: 100vw;
  background-color: #0099FF;
}
</style>