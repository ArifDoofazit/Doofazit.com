<script setup>
import mobileNavbar from './mobileNavbar.vue';
import 'flowbite';
// document.addEventListener("DOMContentLoaded", function() {
//     var navbar = document.getElementById("myNavbar");

//     // Event listener for scroll event
//     window.addEventListener("scroll", function() {
//       // Check if the scroll position is greater than 10 pixels
//       if (window.scrollY > 10) {
//         // Add a class to change the background color
//         navbar.classList.add("bg-white");
//       } else {
//         // Remove the class if the scroll position is less than or equal to 10 pixels
//         navbar.classList.remove("bg-white");
//       }
//     });
//   });
</script>

<template>
  <mobileNavbar></mobileNavbar>
  
<nav id="myNavbar" class="hidden lg:block bg-white z-40 lg:fixed w-full p-2 top-0 h-auto">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto lg:p-2">
    <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse ml-8">
        <img src="../assets/logo/logo.png" class="logo lg:w-56" alt="Doofazit-Logo" />
    </a>
    <button data-collapse-toggle="navbar-dropdown" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-dropdown" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
    </button>
    <div class="hidden w-full md:block md:w-auto" id="navbar-dropdownd">
      <ul class="flex flex-col lg:font-semibold lg:text-lg p-4 md:p-0 mt-4 md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0">
        <li>
            <button id="dropdownNavbarLink12" data-dropdown-toggle="dropdownNavbar12" class="flex items-center justify-between w-full py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:border-gray-700 dark:hover:bg-gray-700 md:dark:hover:bg-transparent font-semibold lg:text-lg">Company <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/></svg>
          </button>
            <!-- Dropdown menu -->
            <div id="dropdownNavbar12" class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow w-52 dark:bg-gray-700 dark:divide-gray-600">
                <ul class="py-2 text-sm text-gray-700 dark:text-gray-400 " aria-labelledby="dropdownLargeButton">
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Message From Founder</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Company Profile</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Technical Area</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Our Happy Client</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Management</a>
                  </li>
                  <li>
                    <a href="#" class="block px-4 py-2 hover:bg-gray-100 hover:text-blue-600 dark:hover:bg-gray-600 dark:hover:text-white text-base">Technical Team</a>
                  </li>
                </ul>
            </div>
        </li>
        <li>
                    <button id="mega-menu-dropdown-buttontb" data-dropdown-toggle="mega-menu-dropdowntb" class="flex items-center justify-between w-full py-2 px-3 font-medium text-gray-900 border-b border-gray-100 md:w-auto hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-blue-600 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-blue-500 md:dark:hover:bg-transparent dark:border-gray-700 lg:font-semibold lg:text-lg">Software<svg class="w-2.5 h-2.5 ms-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                      <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                    </svg>
                    </button>
                    <div id="mega-menu-dropdowntb" class="absolute z-10 grid hidden lg:w-4/5 lg:ml-10 text-sm bg-white border border-gray-100 rounded-lg shadow-md dark:border-gray-700 dark:bg-gray-700">
                     <!-- =====================teb=================== -->
                      <div class="p-12 pb-0 text-gray-900 md:pb-12 dark:text-white">
                          <div class="md:flex">
                              <ul id="default-tab" data-tabs-toggle="#default-tab-content" class="lg:w-60 lg:text-base flex-column space-y space-y-4 text-sm font-medium text-gray-500 dark:text-gray-400 md:me-4 mb-4 md:mb-0">
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100" id="Business-tab" data-tabs-target="#Business" type="button" role="tab" aria-controls="Business" aria-selected="false">Business Solution</button>
                                </li>
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100 hover:border-gray-300 dark:hover:text-gray-300" id="Blockchain-tab" data-tabs-target="#Blockchain" type="button" role="tab" aria-controls="Blockchain" aria-selected="false">Blockchain</button>
                                </li>
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100 hover:border-gray-300 dark:hover:text-gray-300" id="Hotel-tab" data-tabs-target="#Hotel" type="button" role="tab" aria-controls="Hotel" aria-selected="false">Hotel & Restaurant</button>
                                </li>
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100 hover:border-gray-300 dark:hover:text-gray-300" id="Ecommerce-tab" data-tabs-target="#Ecommerce" type="button" role="tab" aria-controls="Ecommerce" aria-selected="false">Ecommerce</button>
                                </li>
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100 hover:border-gray-300 dark:hover:text-gray-300" id="Education-tab" data-tabs-target="#Education" type="button" role="tab" aria-controls="Education" aria-selected="false">Education</button>
                                </li>
                                <li class="" role="presentation">
                                    <button class="inline-block p-2 border-b-2 hover:text-green-600 w-full text-justify hover:bg-green-100 hover:border-gray-300 dark:hover:text-gray-300" id="Health-tab" data-tabs-target="#Health" type="button" role="tab" aria-controls="Health" aria-selected="false">Health</button>
                                </li>
                              </ul>
                              <div id="default-tab-content">
<!-- ============================Business======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Business" role="tabpanel" aria-labelledby="Business-tab">
                                    <div class="grid gap-4 grid-cols-3">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/HR-Manager.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> HR Manager<br> <span class="text-sm">Human Resource Management</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Sales-ERP.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> ERP<br> <span class="text-sm">Business ERP Solution / Company Management</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/M-store.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> M-Store <br> <span class="text-sm">Multi-Store Inventory Management</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Wholesale.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Wholesale <br> <span class="text-sm">Inventory Management System</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent relati block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Innue.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Innue <br> <span class="text-sm">Business Live Chatbot Software</span></h5>
                                        </a>
                                      </div>
                                    </div>
                                  </div>
<!-- ==============================Business End======================================== -->

<!-- ============================Blockchain======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Blockchain" role="tabpanel" aria-labelledby="Blockchain-tab">
                                    <div class="grid gap-4 grid-cols-3">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/NFTBox.webp" alt="image-HR">
                                              <h5 class="ml-5 float-left text-xl font-semibold"> NFTBOX<br> <span class="text-sm">NFT Marketplace Script</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Tradebox.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Tradebox<br> <span class="text-sm">CryptoCurrency Buy Sell and Trading Software</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Nisshue.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Nishue<br> <span class="text-sm">CryptoCurrency Buy Sell with MLM System</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/ICO-Wallet.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> ICO Wallet<br> <span class="text-sm">ICO Software and Token Launching Solution</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent relati block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Tokenbox.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Tokenbox<br> <span class="text-sm">Best Security Token Offering Platform (STO)</span></h5>
                                        </a>
                                      </div>
                                    </div>
                                  </div>
<!-- ============================Blockchain End======================================= -->

<!-- ============================Hotel======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Hotel" role="tabpanel" aria-labelledby="Hotel-tab">
                                    <div class="grid gap-4 grid-cols-3">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/Bhojon.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Bhojon<br> <span class="text-sm">Restaurant Management Software</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Cloud-KItchen.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Cloud Kitchen<br> <span class="text-sm">Kitchen Management Software</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Xain.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Xain Hotel<br> <span class="text-sm">Hotel Management System & Booking Software</span></h5>
                                        </a>
                                      </div>
                                    </div> 
                                  </div>
<!-- ============================Hotel End======================================= -->

<!-- ============================Ecommerce======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Ecommerce" role="tabpanel" aria-labelledby="Ecommerce-tab">
                                    <div class="grid gap-4 grid-cols-2">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/Isshue.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-8 float-left text-xl font-semibold"> Isshue<br> <span class="text-sm">Multi Store eCommerce Shopping Cart Solution</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Storefex.webp" alt="image-HR">
                                              <h5 class="ml-5 float-left text-xl font-semibold"> Storefex<br> <span class="text-sm">Multi Vendor Marketplace Platform</span></h5>
                                        </a>
                                      </div>
                                    </div> 
                                  </div>
<!-- ============================Ecommerce End======================================= -->

<!-- ============================Education======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Education" role="tabpanel" aria-labelledby="Education-tab">
                                    <div class="grid gap-4 grid-cols-2">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/Quizguru.webp" alt="image-HR">
                                              <h5 class="ml-5 float-left text-xl font-semibold"> Quizguru<br> <span class="text-sm">Online Exam System PHP Script</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Edutask.webp" alt="image-HR">
                                              <h5 class="ml-5 float-left text-xl font-semibold"> Edutask<br> <span class="text-sm">Online Course Selling Marketplace</span></h5>
                                        </a>
                                      </div>
                                    </div>  
                                  </div>
<!-- ============================Education End======================================= -->

<!-- ============================Health======================================= -->
                                  <div class="hidden p-4 rounded-lg bg-gray-50 dark:bg-gray-800" id="Health" role="tabpanel" aria-labelledby="Health-tab">
                                    <div class="grid gap-4 grid-cols-3">
                                      <div>
                                            <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                              <img class="w-10 float-left" src="../assets/dropdown/Hospital-Automanager.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold">Automanager<br> <span class="text-sm">Advance Hospital Management System Software</span></h5>
                                            </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Hospital.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Hospital<br> <span class="text-sm">Hospital Management System</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Pharmacare.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Pharmacare<br> <span class="text-sm">Pharmacy Management System</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Multi-Hospital.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Multi-Hospital<br> <span class="text-sm">Best Hospital Management System (SaaS App)</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent relati block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Doctorss.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Doctorss<br> <span class="text-sm">Doctor Appointment and Prescription System</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-green-100 to-transparent relati block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/G-Prescription.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> G-Prescription<br> <span class="text-sm">Gynaecology & OBS Consultation Software</span></h5>
                                        </a>
                                      </div>
                                      <div>
                                        <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent relati block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-36">
                                          <img class="w-10 float-left" src="../assets/dropdown/Clinic-365.webp" alt="image-HR">
                                              <h5 class="ml-14 -mt-11 float-left text-xl font-semibold"> Clinic365<br> <span class="text-sm">Clinic Management System</span></h5>
                                        </a>
                                      </div>
                                    </div>
                                  </div>
<!-- ============================Health End======================================= -->
                              </div>
                          </div>
                        </div>
                        <!-- =================teb End====================== -->
                    </div>
                </li>
        <li>
          <a href="#" class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent font-semibold lg:text-lg">Website</a>
        </li>
<!-- =========================Digital Marketing======================== -->
          <li>
            <button id="dropdownNavbarLinkme" data-dropdown-toggle="dropdownNavbarme" class="flex items-center justify-between w-full py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:border-gray-700 dark:hover:bg-gray-700 md:dark:hover:bg-transparent font-semibold lg:text-lg">Digital Marketing<svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/></svg>
          </button>
            <!-- Dropdown menu -->
            <div id="dropdownNavbarme" class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow lg:w-auto dark:bg-gray-700 dark:divide-gray-600">
                <ul class="py-2 text-sm text-gray-700 dark:text-gray-400" aria-labelledby="dropdownLargeButton">
                    <li>
                      <div class="grid gap-4 px-5 grid-cols-2">
                          <div>
                              <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-28">
                                <img class="w-10 float-left" src="../assets/dropdown/Isshue (1).webp" alt="image-HR">
                                <h5 class=" lg:ml-5 float-left text-xl font-semibold"> Isshue Apps<br> <span class="text-sm">Ecommerce Android Apps</span></h5>
                              </a>
                          </div>
                        <div>
                          <a href="#" class="bg-gradient-to-r from-blue-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-28">
                            <img class="w-10 float-left" src="../assets/dropdown/Bhojon (1).webp" alt="image-HR">
                            <h5 class="lg:ml-5 float-left text-xl font-semibold"> Bhojon Android Apps<br> <span class="text-sm">Restaurant Management Apps</span></h5>
                          </a>
                        </div>
                        <div>
                          <a href="#" class="bg-gradient-to-r from-purple-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-28">
                            <img class="w-10 float-left" src="../assets/dropdown/News365.webp" alt="image-HR">
                            <h5 class="lg:ml-5 float-left text-xl font-semibold"> Edutask<br> <span class="text-sm">Online Course Selling Marketplace</span></h5>
                          </a>
                        </div>
                        <div>
                          <a href="#" class="bg-gradient-to-r from-green-100 to-transparent block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 lg:h-28">
                            <img class="w-10 float-left" src="../assets/dropdown/m-store.png" alt="image-HR">
                            <h5 class="lg:ml-5 float-left text-xl font-semibold"> Mops Apps<br> <span class="text-sm">Sales ERP Apps</span></h5>
                          </a>
                        </div>
                      </div> 
                    </li>
                  </ul>
              </div> 
        </li>
<!-- =========================Digital Marketing End======================== -->
        <li>
          <a href="#" class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent font-semibold lg:text-lg">Payment</a>
        </li>
      </ul>
    </div>

    <div class="hot-line">
      <a href="#" class="text-xl text-red-600 lg:ml-4"><span class=" "><i class="fa-solid fa-phone-volume"></i></span> Need any help?</a>
      <h2 class="text-xl"> Call:+8801884-724029</h2>
    </div>

    <button type="button" class="ml-4 text-white bg-blue-700 hover:bg-blue-800 font-medium rounded-lg text-sm px-4 py-2 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800 object-none w-28 h-9">Get started</button>
  </div>
  
</nav>

</template>
<style scoped>
 #default-tab li button {
      background-image: linear-gradient(to right, #ffffff 0%, #b3f5d6 100%);
      background-size: 200% 100%;
      transition: background-position 0.5s ease;
    }
    #default-tab li button:hover {
      background-position: -100% 0;
    }
.bg-white {
    background-color: white !important;
  }
.logo{
  margin-left: -40px;
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
    #mega-menu-dropdowntb{
      margin-top: 20px !important;
      margin-left: 10% !important;
      border-top: 6px solid #2eb71e;
    }
    #dropdownNavbar12{
      margin-top: 20px !important;
      border-top: 6px solid #2eb71e;
    }
    #dropdownNavbarme{
      margin-top: 20px !important;
      margin-left: 5% !important;
      border-top: 6px solid #2eb71e;
    }
/* @media all and (min-width:320px) and (max-width:780px){
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
  #dropdownNavbar{
      border-top: 4px solid #2eb71e;
    }
  .logo{
  margin-left: 0px;
}
} */
</style>