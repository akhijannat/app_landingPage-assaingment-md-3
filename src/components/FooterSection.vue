<script setup>
  const footerItem = "flex flex-col text-lg space-y-2"
  const footerHeading = "text-2xl md:text-3xl font-bold py-4"
</script>

<template>
    <footer class="bg-gray-800 text-white py-8 md:py-16">
      <div class="container mx-auto px-4 md:px-10">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
          <div>
            <img src="../assets/logo.svg" alt="">
            <button class="border bg-gray-600 mt-4 py-2 px-4 text-xl rounded-md text-white">Download App</button>
          </div>
          <div :class="footerItem">
            <h2 :class="footerHeading">About Us</h2>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
          </div>
          <div :class="footerItem">
            <h2 :class="footerHeading">About</h2>
            <a href="#">Partners</a>
            <a href="#">Terms of Service</a>
            <a href="#">Privacy Policy</a>
            <a href="#">Refund Policy</a>
          </div>
          <div :class="footerItem">
            <h2 :class="footerHeading">Support</h2>
            <a href="#">Open Ticket</a>
            <a href="#">Community</a>
            <a href="#">Return Policy</a>
            <a href="#">Accessibility</a>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped></style>
  