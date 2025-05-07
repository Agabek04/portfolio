<template>
  <div class="w-full text-4xl">
    <div class="text-center text-5xl mb-10 text-blue-100">
      <p>My projects</p>
    </div>
    <div class="overflow-hidden mt-10 mb-10 hover:bg-blue-500 w-full h-[398px]">
      <img :src="flag" class="float-left mr-10 ml-10 mt-3 w-140 h-auto rounded-3xl" >
      <a href="https://github.com/Agabek04/css-flag.git"> <p class=" font-semibold text-white mt-30 text-center hover:text-blue-900">Css Flag Project</p></a>
    </div>
    <div class="overflow-hidden mt-10 mb-10 mr-10 hover:bg-blue-500 w-full h-[510px]">
      <img :src="grid" class="float-right ml-10 mt-4 mr-10 w-120 h-auto rounded-3xl" >
      <a href="https://github.com/Agabek04/grid.git"><p class=" font-semibold text-white mt-30 text-center hover:text-blue-900">Mondrian Project</p></a>
    </div>
    <div class="overflow-hidden mt-10 mb-10 hover:bg-blue-500 w-full h-[452px]">
      <img :src="dice" class="float-left mr-10 ml-10 mt-3 w-150 h-auto rounded-3xl" >
      <a href="https://github.com/Agabek04/dice.git"><p class=" font-semibold text-white mt-30 text-center hover:text-blue-900">Dice Game</p></a>
    </div>
    <div class="overflow-hidden mt-10 mb-10 hover:bg-blue-500 w-full h-[370px]">
      <img :src="drumkit" class="float-right mr-10 ml-10 mt-4 w-150 h-[340px] rounded-3xl" >
      <a href="https://github.com/Agabek04/drum-kit.git"><p class=" font-semibold text-white mt-30 text-center hover:text-blue-900">Drum Kit</p></a>
    </div>
    <div class="overflow-hidden mt-10 mb-10 hover:bg-blue-500 w-full h-[555px]">
      <img :src="simongame" class="float-left mt-4 ml-10 w-120 h-auto rounded-3xl" >
      <a href="https://github.com/Agabek04/simon-game.git"><p class=" font-semibold text-white mt-30 text-center hover:text-blue-900">Simon Game</p></a>
    </div>
    <div class=" text-end mr-20 mb-15 text-white h-16">
      <a href="https://github.com/Agabek04/bootcamp.git" class="text-blue-300 underline ">Here</a><span> you can see my other projects</span>
    </div>
  </div>
  </template>
  
  <script setup>
  import flag from '../assets/images/flag.png'
  import drumkit from '../assets/images/drumkit.png'
  import simongame from '../assets/images/simongame.png'
  import dice from '../assets/images/dice.png'
  import grid from '../assets/images/grid.png'
  </script>

