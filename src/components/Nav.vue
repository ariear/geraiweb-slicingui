<template>
  <nav class="font-pupylinux text-white fixed flex items-center justify-between container left-0 right-0 mx-auto py-9 z-40 px-4 md:px-8 xl:px-0 anjim transition-all">
      <p class="font-medium text-4xl md:block hidden">Gerai<span class="font-light">Web</span></p>
      <p class="font-medium text-3xl md:hidden block">G<span class="font-light">W.</span></p>
      <div class="hidden md:flex items-center font-normal text-lg">
          <p class="mr-8"><a href="#home">Home</a></p>
          <p class="mr-8"><a href="#pricing">Pricing</a></p>
          <p class="mr-8"><a href="#services">Services</a></p>
          <p><a href="#contact">Contact</a></p>
      </div>
  </nav>
</template>

<script>
export default {
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