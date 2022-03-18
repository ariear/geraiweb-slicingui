<template>
<div class="font-pupylinux pt-28 md:pt-64 pb-32" id="pricing">
    <div class="text-center">
        <p class="font-semibold text-[#044581] text-[30px] md:text-[40px]">Our <span class="font-normal">Pricing</span></p>
        <p class="font-normal text-base md:text-lg text-[#363636]">Penawaran terbaik untuk anda</p>
    </div>

    <div class="flex flex-wrap justify-center mt-16">
    <!-- card -->
        <div class="w-[250px] shadow-md bg-white text-center relative overflow-hidden rounded-lg">
            <div class="w-[120%] h-[100px] absolute bg-[#0099FF] -rotate-6 -left-3 -top-7"></div>
            <p class="font-semibold text-white text-2xl z-40 relative pt-5">BASIC</p>
            <p class="font-semibold text-[#363636] text-2xl mt-14">20k/<span class="text-base">Project</span></p>
            <div class="my-7 font-light">
                <p>Responsive Web</p>
                <p class="my-2">Beautiful Web</p>
                <p>Effect Cool</p>
            </div>
            <button class="py-3 px-7 rounded-xl btn-linear-gradient mb-8 text-white font-semibold">Get This</button>
        </div>
        <div class="w-[250px] shadow-md bg-[#0099FF] text-center relative overflow-hidden rounded-lg mx-9 mt-9 md:mt-0">
            <div class="w-[120%] h-[70px] absolute top-0 bg-white rounded-b-[120%] -left-6"></div>
            <p class="font-semibold text-[#0099FF] text-2xl z-40 relative pt-5">Standart</p>
            <p class="font-semibold text-white text-2xl mt-14">20k/<span class="text-base">Project</span></p>
            <div class="my-7 font-light text-white">
                <p>Responsive Web</p>
                <p class="my-2">Beautiful Web</p>
                <p>Effect Cool</p>
            </div>
            <button class="py-3 px-7 rounded-xl bg-white mb-8 text-[#0099FF] font-semibold">Get This</button>
        </div>
        <div class="w-[250px] shadow-md bg-white text-center relative overflow-hidden rounded-lg mt-9 lg:mt-0">
            <div class="w-[120%] h-[100px] absolute bg-[#0099FF] -rotate-6 -left-3 -top-7"></div>
            <p class="font-semibold text-white text-2xl z-40 relative pt-5">Premium</p>
            <p class="font-semibold text-[#363636] text-2xl mt-14">1000000k/<span class="text-base">Project</span></p>
            <div class="my-7 font-light">
                <p>Website And Deploy</p>
                <p class="my-2">Free Domain</p>
                <p>Effect Cool</p>
            </div>
            <button class="py-3 px-7 rounded-xl btn-linear-gradient mb-8 text-white font-semibold">Get This</button>
        </div>
    <!-- end card -->
    </div>

</div>  
</template>

<script>
export default {

}
</script>

<style>
.btn-linear-gradient{
    background: rgb(0,153,255);
background: linear-gradient(107deg, rgba(0,153,255,1) 21%, rgba(95,213,251,1) 82%);
}
</style>
