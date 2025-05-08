<template>
  <div class="h-[650px]">
    <div class="w-full h-[320px] text-white text-2xl mt-10">
      <div class="w-[500px] mt-30 ml-10">
        <p class="ml-10">CONTACT ME</p>
        <div class="flex mt-10">
          <img :src="location" class="w-[32px] h-[36px] mr-2" />
          <p class="mt-2">Ashgabat city, Turkmenistan</p>
        </div>
        <div class="flex mt-5">
          <img :src="call" class="w-[37px] h-[39px] mr-2" />
          <p class="mt-3">Phone: <span class="ml-2">+99363672841</span></p>
        </div>
        <div class="flex mt-5">
          <img :src="email" class="w-[35px] h-[29px] mr-2" />
          <p>Email: matyakubow.agabek04@gmail.com</p>
        </div>
        <div class="flex justify-between w-[180px] mt-10">
          <div class="w-[45px] h-[45px] relative">
            <div class="bg-white opacity-33 w-[45px] h-[45px] rounded-sm"></div>

            <a href="https://www.instagram.com/matyakubow.agabek/"
              ><img :src="insta" class="absolute left-2 top-2"
            /></a>
          </div>
          <button class="w-[45px] h-[45px] relative">
            <div class="bg-white opacity-33 w-[45px] h-[45px] rounded-sm"></div>

            <a href="https://imo.im/?lang=ru"
              ><img :src="imo" class="absolute left-1 top-0 w-[40px] h-[45px]"
            /></a>
          </button>
          <button class="w-[45px] h-[45px] relative">
            <div class="bg-white opacity-33 w-[45px] h-[45px] rounded-sm"></div>

            <a href="https://www.facebook.com/?locale=ru_RU">
              <img
                :src="facebook"
                class="absolute left-2 top-2 w-[29px] h-[34px]"
            /></a>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import location from "../assets/images/location.png";
import call from "../assets/images/call.png";
import email from "../assets/images/email.png";
import imo from "../assets/images/imo.png";
import insta from "../assets/images/insta.png";
import facebook from "../assets/images/facebook.png";
</script>