<script setup>

</script>
<template>
    <section id="slider">
        <div class="container mx-auto">
            <div class="grid gap-x-8 gap-y-4 lg:grid-cols-2 sm:grid-cols-2">
                <div >
                    <h1 class="ittext text-center lg:mt-32 lg:text-6xl text-2xl lg:text-white text-gray-50 lg:font-bold cursor-pointer font-bold mt-2">IT Consulting Services For Your Business</h1>
                    <p class="lg:text-white lg:text-2xl lg:mt-5 text-gray-50 text-sm mt-2 lg:px-0 px-5 cursor-pointer">We are leading technology solutions providing company all over the world doing over 40 years.</p>
                </div>
                <!-- ==========Slider-Card================= -->
                <div class="lg:mt-32 lg:ml-56 text-center lg:block hidden">
                    <div class="container mx-auto">
                        <div class="w-full max-w-sm p-4 bg-white border border-gray-200 rounded-lg shadow sm:p-6 md:p-8 dark:bg-gray-800 dark:border-gray-700">
                            <form class="space-y-6" action="#">
                                <h5 class="text-xl font-medium text-gray-900 dark:text-white">Sign in to our platform</h5>
                                <div>
                                    <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white text-justify	">Your email</label>
                                    <input type="email" name="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white" placeholder="name@gmail.com" required />
                                </div>
                                <div>
                                    <label for="password" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white text-justify	">Your password</label>
                                    <input type="password" name="password" id="password" placeholder="passwoed" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white" required />
                                </div>
                                <div class="flex items-start">
                                    <div class="flex items-start">
                                        <div class="flex items-center h-5">
                                            <input id="remember" type="checkbox" value="" class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800" required />
                                        </div>
                                        <label for="remember" class="ms-2 text-sm font-medium text-gray-900 dark:text-gray-300">Remember me</label>
                                    </div>
                                    <a href="#" class="ms-auto text-sm text-blue-700 hover:underline dark:text-blue-500">Lost Password?</a>
                                </div>
                                <button type="submit" class="w-full text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Login to your account</button>
                                <div class="text-sm font-medium text-gray-500 dark:text-gray-300">
                                    Not registered? <a href="#" class="text-blue-700 hover:underline dark:text-blue-500">Create account</a>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <!-- ==================Slider-Card End================== -->
            </div>
        </div>
    </section>
</template>
 <style scoped>
 #slider{
    width: 100%;
    background-image: url(../assets/slider/banner-1.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 650px !important;
 }
 .ittext{
    line-height: 80px !important;
 }
 @media all and (min-width:320px) and (max-width:780px){
    #slider{
    width: 100%;
    background-image: url(../assets/slider/banner-1.jpg);
    background-size: contain;
    background-repeat: no-repeat;
    margin-top: 20%;
    height: 174px !important;
 } 
 .ittext{
    line-height: 30px !important;
 }
 }
</style>   