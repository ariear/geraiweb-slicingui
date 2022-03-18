<template>
  <div class="pt-5 pb-28 text-center" id="services">
      <p class="font-semibold text-3xl md:text-5xl text-[#044581]">Our <span class="font-light">Services</span></p>
      <p class="font-normal text-base md:text-xl mt-2 md:mt-4 mb-8">Layanan yang kita tawarkan untuk anda</p>

      <div class="mx-auto flex flex-wrap md:w-[690px] lg:w-[990px] justify-center">
          <div v-for="(service , index) in dataService" :key="index" class="w-[300px] py-7 text-center shadow-card rounded-xl px-4 mx-3 mt-8">
              <img src="/asset/comp-icon.png" class="mx-auto" alt="">
              <p class="font-medium text-xl text-[#012D56] mt-4">{{ service.main }}</p>
              <p class="mt-3 font-normal text-[#363636]">{{ service.more }}</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            dataService: [
                {
                    img: '/asset/comp-icon.png',
                    main: 'Website Personal',
                    more: 'Website Yang Cantik Dan Responsive Untuk Portofolio Anda'
                },
                {
                    img: '/asset/comp-icon.png',
                    main: 'Website Company',
                    more: 'Di era sekarang ini gak afdol dong perusahaan yang gak punya website'
                },
                {
                    img: '/asset/comp-icon.png',
                    main: 'Hosting',
                    more: 'Hosting yang sangat aman dan cepat'
                },
                {
                    img: '/asset/comp-icon.png',
                    main: 'Cloud Storage',
                    more: 'Cloud storage yang bisa menyimpan forno dan gravure'
                },
                {
                    img: '/asset/comp-icon.png',
                    main: 'Website Personal',
                    more: 'Website Yang Cantik Dan Responsive Untuk Portofolio Anda'
                },
            ]
        }
    },
}
</script>

<style>
.shadow-card{
box-shadow: -1px 3px 25px -1px rgba(0,0,0,0.3);
-webkit-box-shadow: -1px 3px 25px -1px rgba(0,0,0,0.3);
-moz-box-shadow: -1px 3px 25px -1px rgba(0,0,0,0.3);
}
</style>