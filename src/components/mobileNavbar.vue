<script setup>
import 'flowbite';
const $targetEl = document.getElementById('modalEl');

// options with default values
const options = {
    placement: 'bottom-right',
    backdrop: 'dynamic',
    backdropClasses:' bg-Function fixed inset-0 z-40',
    closable: true,
    onHide: () => {
        console.log('modal is hidden');
    },
    onShow: () => {
        console.log('modal is shown');
    },
    onToggle: () => {
        console.log('modal has been toggled');
    },
};

// instance options object
const instanceOptions = {
  id: 'modalEl',
  override: true
};

</script>

<template>
<nav class="md:flex lg:hidden sm:block bg-white z-50 fixed w-full p-2 top-0 h-auto">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">

  <div class="block space-y-4 md:flex md:space-y-0 md:space-x-4 md:rtl:space-x-reverse">
    <button data-modal-target="top-left-modal" data-modal-toggle="top-left-modal" class="block w-full md:w-auto text-blue-500 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" type="button">
      <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5 text-blue-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
    </button>
  </div>

    <a href="#" class="logo-container animate-left-to-right">
      <img src="../assets/logo/logo.png" class="w-64 -ml-5" alt="Doofazit-Logo"/>
    </a>
<!-- =================================modal========================== -->
<div id="top-left-modal" data-modal-placement="top-left" tabindex="-1" class="animate-left-to-right fixed top-0 left-0 right-0 z-50 hidden w-80 p-4 overflow-y-auto max-h-full">
    <div class="relative w-full max-w-2xl max-h-full">
        <!-- Modal content -->
        <div class="relative bg-white rounded-lg shadow">
            <!-- Modal header -->
            <div class="flex items-center justify-between p-4 md:p-5 border-b rounded-t dark:border-gray-600">
              <a href="#" class="logo-container animate-right-to-left">
                  <img src="../assets/logo/logo.png" class="w-auto" alt="Doofazit-Logo"/>
              </a>
                <button type="button" class="text-gray-400 rounded-lg text-sm w-8 h-8 ms-auto inline-flex justify-center items-center dark:hover:text-white" data-modal-hide="top-left-modal" style="border: 2px solid red;">
                    <svg class="w-3 h-3 text-red-600 font-bold" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
                    </svg>
                    <span class="sr-only">Close modal</span>
                </button>
            </div>
            
            <!-- Modal footer -->
      <ul class="animate-left-to-right flex flex-col font-medium h-auto p-4 md:p-0 mt-4 md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 dark:border-gray-700">
        <!-- ===================================Company================================ -->

            <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group dark:text-white" aria-controls="dropdownNavbar" data-collapse-toggle="dropdownNavbar">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">Company</span>
                  <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                     <path class="text-blue-500" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                  </svg>
            </button>
              <ul id="dropdownNavbar" class="hidden py-2 space-y-2">
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Message From Founder</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Company Profile</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Technical Area </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Our Happy Client</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Management</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Technical Team</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Doofaz Training Institute (DTI)</a>
                  </li>
                </ul>
<!-- ===================================Company End================================ -->

  <!-- ===================================softower================================ -->
            <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700" aria-controls="dropdownNavbar-sf" data-collapse-toggle="dropdownNavbar-sf">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">Software</span>
                  <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                     <path class="text-blue-500" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                  </svg>
            </button>
              <ul id="dropdownNavbar-sf" class="hidden py-2 space-y-2">
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Online POS  (সব ধরনের ব্যাবসার জন্য) </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Business ERP(Completed Solutions) </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Trasnport ERP </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Accounting/Inventory </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Human Resource-HRM </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> School  Management</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> সকল দোকান দারদের জন্য(POS) </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Pharmacy Management </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Hospital Management </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> MLM Software </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Tours & Travels </a>
                  </li>
                </ul>
<!-- ===================================softower End================================ -->

<!-- ===================================Website End================================ -->
            <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700" aria-controls="dropdownNavbarwe" data-collapse-toggle="dropdownNavbarwe">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">Website</span>
                  <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                     <path class="text-blue-500" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                  </svg>
            </button>
              <ul id="dropdownNavbarwe" class="hidden py-2 space-y-2">
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> E-Commerce Service</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Online News Portal</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Personal Branding Website</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Requirement Based Website </a>
                  </li>
                </ul>

<!-- ===================================Website End================================ -->

<!-- =================================Digital Marketing================================== -->

            <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700" aria-controls="dropdownNavbar-dg" data-collapse-toggle="dropdownNavbar-dg">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">Digital Marketing</span>
                  <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                     <path class="text-blue-500" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                  </svg>
            </button>
              <ul id="dropdownNavbar-dg" class="hidden py-2 space-y-2">
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Email Marketing</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Social Media Marketing </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Facebook Boosting Package </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Facebook Page Like </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Search Engine Optimization  </a>
                  </li>
                </ul>
<!-- =================================Digital Marketing End================================== -->

<!-- ========================SMS Marketing============================ -->

            <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700" aria-controls="dropdownNavbar-sm" data-collapse-toggle="dropdownNavbar-sm">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">SMS Marketing</span>
                  <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                     <path class="text-blue-500" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                  </svg>
            </button>
              <ul id="dropdownNavbar-sm" class="hidden py-2 space-y-2">
                <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> SMS Rate </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Authorization Letter </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> SMS Database </a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 dark:hover:bg-gray-600 dark:hover:text-white"><i class="fa-solid fa-paper-plane text-red-500"></i> Hosting</a>
                  </li>
                </ul>
<!-- ========================SMS Marketing End============================ -->

              <button type="button" class="flex items-center w-full p-2 text-base text-gray-900 transition duration-75 rounded-lg group hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700">
                  <span class="flex-1 ms-3 text-left rtl:text-right whitespace-nowrap text-lg font-bold">Payment</span>
              </button>
      </ul>
    </div>   
        </div>
    </div>
<!-- ========================Modal End=======================-->
</div>
</nav>

</template>

<style scoped>
#top-left-modal{
  border: 4px solid #000000;
  background: #4097c7;
}

@keyframes slideFromLeft {
    from {
        transform: translateX(-100%);
        opacity: 0;
    }
    to {
        transform: translateX(0);
        opacity: 1;
    }
}
#default-tabone li a {
  background-image: linear-gradient(to right, #ffffff 0%, #b3f5d6 100%);
  background-size: 200% 100%;
  transition: background-position 0.5s ease;
}
#default-tabone li a:hover {
  background-position: -100% 0;
}

#default-tab li a {
  background-image: linear-gradient(to right, #ffffff 0%, #b3f5d6 100%);
  background-size: 200% 100%;
  transition: background-position 0.5s ease;
}
#default-tab{
  border-radius: 10px;
  border: 1px solid rgb(3, 154, 201);
}
#default-tab li a:hover {
  background-position: -100% 0;
}
.animate-left-to-right {
    animation: slideFromLeft 1s ease;
}

.animate-right-to-left { 
    animation: rightToLeftAnimation 1s ease-in-out;
}

@keyframes rightToLeftAnimation {
    from {
        transform: translateX(100%);
    }
    to {
        transform: translateX(0);
    }
}

  .hot-line span i{
     color: red;
   }
   .hot-line span i:hover{
    zoom: 1.2;
   }
   .text-green-500 {
    margin-left: 25px 
    }
    #mega-menu-dropdown{
      border-top: 4px solid #2eb71e;
    }
@media all and (min-width:320px) and (max-width:780px){
  .hot-line{
    display:none;
  }
  .text-white {
    display: none;
}
#mega-menu-dropdown{
    width: 95%;
    border-top: 4px solid #2eb71e;
  }
}
</style>