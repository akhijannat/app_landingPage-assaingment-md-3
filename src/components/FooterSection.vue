<script setup>
const footerItem = "flex flex-col inline-block text-lg space-y-2";
const footerHeading = "text-2xl md:text-3xl font-bold py-4";
const footerItemLink = "ease-in duration-300 hover:text-[#e8505b]";
</script>

<template>
  <footer class="bg-gray-800 text-white py-8 md:py-16">
    <div class="container mx-auto px-4 md:px-10">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
        <div>
          <img src="../assets/logo-2.svg" alt="" />
          <button
            class="border bg-gray-600 mt-4 py-2 px-4 text-xl rounded-md text-white"
          >
            Download App
          </button>
        </div>
        <div :class="footerItem">
          <h2 :class="footerHeading">About Us</h2>
          <ul>
            <li><a :class="footerItemLink" href="#home">Home</a></li>
            <li><a :class="footerItemLink" href="#services">Services</a></li>
            <li><a :class="footerItemLink" href="#about">About Us</a></li>
            <li><a :class="footerItemLink" href="#contact">Contact</a></li>
          </ul>
        </div>
        <div :class="footerItem">
          <h2 :class="footerHeading">About</h2>
          <ul>
            <li><a :class="footerItemLink" href="#">Partners</a></li>
            <li><a :class="footerItemLink" href="#">Terms of Service</a></li>
            <li><a :class="footerItemLink" href="#">Privacy Policy</a></li>
            <li><a :class="footerItemLink" href="#">Refund Policy</a></li>
          </ul>
        </div>
        <div :class="footerItem">
          <h2 :class="footerHeading">Support</h2>
          <ul>
            <li><a :class="footerItemLink" href="#">Open Ticket</a></li>
            <li><a :class="footerItemLink" href="#">Community</a></li>
            <li><a :class="footerItemLink" href="#">Return Policy</a></li>
            <li><a :class="footerItemLink" href="#">Accessibility</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
