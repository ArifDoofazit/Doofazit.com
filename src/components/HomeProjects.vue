<script setup>

</script>

<template>
    <section id="project">
        <div class="Title">
            <div class="container mx-auto">
                <!-- <h2 class="cursor-pointer text-center text-gray-50 text-4xl lg:text-4xl lg:font-semibold z-10 relative lg:text-white mt-5 font-bold">Featured Projects</h2>
                <p class="cursor-pointer lg:text-lg z-10 relative text-white lg:text-justify text-center px-5 mt-5">Roopokar has got the privilege to serve around 200 clients around the globe. Group of Companies, Agencies, Startups, NGOs, Government in every sector we have worked with several big names. Our clients are like our partner. We work together to accomplish common goals.</p> -->
                
                <div class="grid gap-4 lg:grid-cols-2 grid-cols-1 ">
                    <div></div>
                    <div class="px-4">
                        <h2 class="cursor-pointer text-center text-gray-50 text-4xl  lg:text-4xl lg:font-semibold z-10 relative mt-5 font-bold">Featured Projects</h2>
                        <p class="cursor-pointer lg:text-base z-10 relative lg:text-justify text-justify px-1 mt-5">See what our clients give us back. We want to share the happiness with you.</p>
                        <p class="cursor-pointer lg:text-lg z-10 relative lg:text-justifytext-justify px-1 mt-5">Efficient, Professional, Pledge, Creativity, Unique, Content and Pricing are just a few great attributes Roopokar Creative Studio. It keeps the word and delivered on as promised. It has been a great pleasure to work with you in our company’s group website. Once our website was up and running, we had innumerable clients questioning about who designed our site, and a large portion just committing on how clean, precise and original, it was. We have continued to get numerous greetings on your effort.</p>
                        <p class="cursor-pointer lg;text-lg px-5 lg:mt-5">Dr Admor de</p>
                    </div>
                </div>
            
            </div>
<!-- ===============================Card-Carousel================================== -->
<!-- ===============================Card-Carousel End================================== -->
        </div>
    </section>
</template>
<style scoped>
    #project{
    width: 100%;
    height: 500px;
    overflow: hidden;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: top;
    z-index: -3;
    background-image: url(../assets/project/client.jpg);
}
/* #project::before {
    position: absolute;
    content: "";
    display: block;
    width: 100%;
    height: 700px;
    left: 0;
    top: 1250px;
    z-index: 1;
    background: #000;
    opacity: .6;
} */
@media all and (min-width:320px) and (max-width:780px){
#project{
    width: 100%;
    height: 620px;
    overflow: hidden;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: top;
    z-index: -3;
    background-image: url(../assets/project/client.jpg);
}
/* #project::before {
    position: absolute;
    content: "";
    display: block;
    width: 100%;
    height: 821px;
    left: 0;
    top: 1082px;
    z-index: 1;
    background: #000;
    opacity: .6;
} */
.text-white {
    display: block;
}
}
</style>