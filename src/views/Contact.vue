<template>
  <div class="font-pupylinux bg-[url('/asset/kantor.png')] bg-cover bg-center pb-28" id="contact">
      <p class="text-center font-semibold text-4xl text-white pt-16">Contact Us</p>

      <div class="bg-white w-[94vw] md:w-[700px] lg:w-[500px] xl:w-[700px] mx-auto mt-56 lg:mt-16 pt-40 lg:pt-12 pb-12 pl-16 pr-16 lg:pl-52 lg:pr-12 relative">
          <!-- box blue -->
          <div class="w-[300px] bg-[#00548C] px-8 py-5 absolute lg:-left-40 lg:top-14 lg:mx-0 rounded-md text-white left-0 -top-44 right-0 mx-auto">
              <p class="font-semibold text-lg">Contact information</p>
              <div class="flex mt-5">
                  <img src="/asset/pin-icon.png" class="w-max h-max mr-4" alt="">
                  <p class="font-light text-sm">Desa Wringintelu , Jl. Slamet Riyadi , Kab Jember, Kec. Puger </p>
              </div>
              <div class="flex mt-5 items-center">
                  <img src="/asset/messages.png" class="w-max h-max mr-4" alt="">
                  <p class="font-light text-sm">Ariebilej@gmail.com</p>
              </div>
              <div class="flex items-center mt-5">
                  <img src="/asset/call.png" class="w-max h-max mr-4" alt="">
                  <p class="font-light text-sm">0881026233067</p>
              </div>

              <div class="flex items-center mt-10">
                  <img src="/asset/facebook.png" alt="">
                  <img src="/asset/twitter.png" class="mx-4" alt="">
                  <img src="/asset/instagram.png" alt="">
              </div>
          </div>
          <!-- end box blue -->

          <p class="font-medium text-2xl mb-5">Send a Message</p>

          <div class="flex flex-wrap justify-between">
          <div class="flex flex-col">
              <label for="name" class="text-[#227AFF] font-medium text-sm mb-1">Your name</label>
              <input type="text" name="name" placeholder="enter your name" class="border-b border-b-black px-3 font-light text-sm w-max pb-1">
          </div>
          <div class="flex flex-col">
              <label for="name" class="text-[#227AFF] font-medium text-sm mb-1 lg:mt-7 xl:mt-0">Mobile Number</label>
              <input type="text" name="name" placeholder="enter mobile number" class="border-b border-b-black px-3 font-light text-sm w-max pb-1">
          </div>
          <div class="flex flex-col">
              <label for="name" class="text-[#227AFF] font-medium text-sm mb-1 mt-7">Subject</label>
              <input type="text" name="name" placeholder="subject anjime" class="border-b border-b-black px-3 font-light text-sm w-max pb-1">
          </div>
          <div class="flex flex-col">
              <label for="name" class="text-[#227AFF] font-medium text-sm mb-1 mt-7">Email</label>
              <input type="email" name="name" placeholder="enter your email address" class="border-b border-b-black px-3 font-light text-sm w-max pb-1">
          </div>
          <div class="flex flex-col">
              <label for="name" class="text-[#227AFF] font-medium text-sm mb-1 mt-7">Write your message here...</label>
              <input type="text" name="name" placeholder="write your message" class="border-b border-b-black px-3 font-light text-sm md:w-[400px] lg:w-max xl:w-[400px] pb-1">
          </div>
          </div>
          <button class="py-3 px-4 font-normal text-sm bg-[#1472FF] text-white rounded-lg mt-7">Send Message</button>
      </div>
  </div>
</template>

<script>
export default {

}
</script>