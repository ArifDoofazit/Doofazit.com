<script setup>

</script>
<template>
    <section id="HomeAbout-area">
        <div class="container mx-auto">
           <div class="grid gap-x-8 gap-y-4 md:grid-cols-2 sm:1">
            <div class="left-area text-4xl z-10 md:py-4 md:px-3 mt-20 px-1">
                <img src="../assets/homeAbout/Gear-Set-Up-Your-Desk-Ergonomically-1315115142.webp" alt="">
            </div>
            <div class="right-list">
                <h2 class="text-center mt-5 text-orange-500 lg:text-4xl text-3xl z-10 relative font-semibold lg:cursor-pointer">About Doofaz IT Limited</h2>
                <p class="hidden lg:block mt-6 z-10 text-justify relative text-center text-white text-lg font-normal w-auto sm:d-none lg:cursor-pointer">DoofazIT Limited is a Software & Website and Mobile Application Development & IT Service Provider Company In Bangladesh. Not Just a Software Company  but we have gained the faith of customer’s  and positioned as one of the best software company in Bangladesh since 2014.We aim to provide  fully interactive and cost-effective solutions establishing a bridge between the digitalization world.</p>
            
                <div class="grid gap-2 grid-cols-2 mb-4 px-2">
                        <ul class="float-left lg:text-lg mt-5 text-blue-500 relative z-10">
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Online POS (সব ধরনের ব্যাবসার জন্য)</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Business ERP(Completed Solutions)</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Trasnport ERP</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Human Resource-HRM</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">সকল দোকান দারদের জন্য(POS)</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Hospital Management</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Tours & Travels</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">খামারিদের সফটওয়্যার</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">সমবায় সমিতি সফটওয়্যার</span></a></li>
                        </ul>
                        <ul class="float-left lg:text-lg mt-5 text-blue-500 relative z-10 ">
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Accounting/Inventory</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">School Management</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Pharmacy Management</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">MLM Software</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">NGO Software</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Real Estate ERP</span></a></li>
                            <li><a href="#"><span class="text-orange-500"><i class="fa-solid fa-circle-check"></i></span> <span class="hover:text-white">Co-Operative Banking Software</span></a></li>
                        </ul>
                </div>

            </div>
           </div>     
        </div>
    </section>
</template>
<style scoped>
#HomeAbout-area{
    width: 100%;
    height: 600px;
    overflow: hidden;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: top;
    z-index: -3;
    background-image: url(../assets/homeAbout/s-l1200.jpg);
}
#HomeAbout-area::before {
    position: absolute;
    content: "";
    display: block;
    width: 100%;
    height: 600px;
    left: 0;
    top: 650px;
    z-index: 1;
    background: #000;
    opacity: .6;
}
@media all and (min-width:320px) and (max-width:780px){
#HomeAbout-area{
    width: 100%;
    height: 820px;
    overflow: hidden;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: top;
    z-index: -3;
    background-image: url(../assets/homeAbout/s-l1200.jpg);
}
#HomeAbout-area::before {
    position: absolute;
    content: "";
    display: block;
    width: 100%;
    height: 820px;
    left: 0;
    top:257px;
    z-index: 1;
    background: #000;
    opacity: .6;
}
}
</style>