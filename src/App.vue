<template>
  <div class="text-gray-700 relative">
    <!-- Header Section -->
    <HeaderSection />
   
    <!-- Hero Section -->
    <HeroSection />

    <!-- Services Section -->
    <ServicesSection />

    <!-- About Section -->
    <AboutSection />

    <!-- Products Section -->
    <ProductsSection />

    <!-- Contactless Delivery Section -->
    <ContactlessDeliverySection />

    <!-- Footer Section -->
    <FooterSection />

    <!-- Back to top -->
    <a href="#home" class="fixed right-5 bottom-5 bg-[#e8505b] text-white p-3 rounded-md animate-bounce">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-7 h-7">
        <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 15.75l7.5-7.5 7.5 7.5" />
      </svg>
    </a>
  </div>
</template>

<script>

import HeaderSection from "./components/HeaderSection.vue";
import HeroSection from "./components/HeroSection.vue";
import ServicesSection from "./components/ServicesSection.vue";
import AboutSection from "./components/AboutSection.vue";
import ProductsSection from "./components/ProductsSection.vue";
import ContactlessDeliverySection from "./components/ContactlessDeliverySection.vue";
import FooterSection from "./components/FooterSection.vue";

export default {
  components: {
    HeaderSection,
    HeroSection,
    ServicesSection,
    AboutSection,
    ProductsSection,
    ContactlessDeliverySection,
    FooterSection,
  },
};
</script>

<style scoped></style>
