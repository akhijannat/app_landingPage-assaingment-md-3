<script setup>
import { ref } from 'vue';

const mobileMenuOpen = ref(false);

const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value;
};
</script>
<template>
  <header class="bg-white py-4 sticky top-0 shadow-sm">
    <div class="container mx-auto px-4 lg:px-10">
      <nav class="relative flex flex-col md:flex-row items-center justify-between">
        <a href="index.html" class="md:mr-0 mr-auto">
          <img src="../assets/logo.svg" alt="Logo" class="h-8">
        </a>
        <button @click="toggleMobileMenu" class="absolute top-0 right-0 ml-auto text-gray-500 focus:outline-none md:hidden">
          <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M3 12h18M3 6h18M3 18h18"></path>
          </svg>

          <!-- <svg  xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
          </svg> -->

        </button>

        <div :class="mobileMenuOpen ? 'flex' : 'hidden'" 
          class="flex-col md:flex md:flex-row md:space-x-3 lg:space-x-6 lg:text-xl font-bold md:items-center">

          <a href="#home" class="hover:text-[#e8505b]">Home</a>
          <a href="#services" class="hover:text-[#e8505b]">Services</a>
          <a href="#about" class="hover:text-[#e8505b]">About</a>
          <a href="#how-it-works" class="hover:text-[#e8505b]">How It Works</a>
          <a href="#received" class="hover:text-[#e8505b]">Received</a>
        </div>
        
        <div :class="mobileMenuOpen ? 'block' : 'hidden'" class="md:flex md:items-center md:mt-0 mt-3">
          <div class="flex space-x-1 lg:space-x-4">
            <button type="submit" class="ease-in duration-300 border border-[#e8505b] text-[#e8505b] hover:bg-[#e8505b] hover:text-white py-1 px-4 rounded-lg font-bold">Sign In</button>
            <button type="submit" class="ease-in duration-300 bg-[#e8505b] border border-[#e8505b] hover:bg-inherit hover:text-[#e8505b] py-1 px-4 rounded-lg font-bold text-white">Register</button>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<style scoped></style>
