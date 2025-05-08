<template>
  <div class="w-full">
    <div class="flex justify-center bg-gray-700 fixed top-0 left-0 w-full border border-b-gray-500">
      <nav
        class="flex justify-between text-white text-2xl h-20 items-center w-[500px]"
      >
        <router-link to="#section1" class="hover:text-blue-400"
          >Home</router-link
        >
        <router-link to="#about" class="hover:text-blue-400">About</router-link>
        <router-link to="#projects" class="hover:text-blue-400"
          >Projects</router-link
        >
        <router-link to="#contact" class="hover:text-blue-400"
          >Contact</router-link
        >
      </nav>
      <router-view></router-view>
    </div>
    <div id="section1" class="h-screen">
      <img
        :src="photo"
        class="overflow-hidden rounded-3xl w-100 h-100 float-right m-30"
      />
      <div class="flex items-center h-150 justify-center">
        <div class="text-white font-bold text-center">
          <p class="text-5xl mb-2">
            Hi, I'm <span class="text-sky-600">Agabek</span>
          </p>
          <p class="text-4xl">Frontend Developer</p>
        </div>
      </div>
    </div>
    <div id="about">
      <About />
    </div>
    <div id="projects">
      <Projects />
    </div>
    <div id="contact">
      <Contact />
    </div>
  </div>
</template>

<script setup>
import About from "./About.vue";
import Projects from "./Projects.vue";
import Contact from "./Contact.vue";
import photo from "../assets/images/myphoto.jpg";
</script>