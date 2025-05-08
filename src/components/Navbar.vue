<template>
  <div class="flex justify-center bg-gray-700">
    <nav
      class="flex justify-between text-white text-2xl h-20 items-center w-[500px] mx-auto"
    >
      <router-link to="/" class="hover:text-blue-400">Home</router-link>
      <router-link to="/about" class="hover:text-blue-400">About</router-link>
      <router-link to="/projects" class="hover:text-blue-400"
        >Projects</router-link
      >
      <router-link to="/contact" class="hover:text-blue-400"
        >Contact</router-link
      >
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scope>
nav a.router-link-exact-active {
  color: #00a6f4;
  font-weight: bold;
}
</style>