<script setup>
const serviceCardStyle =
  "ease-in duration-300 p-4 md:p-6 md:block flex flex-col justify-center rounded-md hover:shadow-2xl";
</script>

<template>
  <section id="services" class="py-8 md:py-16">
    <div class="container mx-auto px-4 md:px-10">
      <div class="text-center pb-8 md:pb-16">
        <p class="text-2xl md:text-3xl pb-2 font-semibold text-[#e8505b]">
          Delivery Services
        </p>
        <h1 class="text-4xl md:text-5xl font-bold">All Essentials You Need</h1>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-1.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Food
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>

        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-2.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Grocery
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>

        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-3.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Furniture
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>

        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-4.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Medicine
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>

        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-5.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Electronics
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>

        <a href="#">
          <div :class="serviceCardStyle">
            <img
              class="h-24"
              src="../assets/services/service-icon-6.svg"
              alt=""
            />
            <h3
              class="text-2xl text-center md:text-left md:text-3xl font-semibold py-4"
            >
              Clothes
            </h3>
            <p class="text-lg md:text-xl">
              Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
              nonumy eirmod tempor invidunt.
            </p>
          </div>
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
