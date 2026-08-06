<script setup lang="ts"></script>
<template>
  <section class="flex items-center justify-center py-20 px-6">
    <div class="w-full max-w-6xl rounded-3xl bg-gradient-to-r from-[#7e097e] via-[#9d2a9c] to-[#bc4ab9] shadow-2xl">
      <div class="flex flex-col-reverse lg:flex-row items-center justify-between gap-12 p-10 md:p-16">
        <!-- Información -->
        <div class="text-white max-w-xl">
          <h1 class="text-4xl md:text-5xl font-bold leading-tight">
            Descarga la app de
            <span class="text-[#fa8bf5]">Sabix Delivery</span>
          </h1>

          <p class="mt-6 text-lg text-purple-100">
            Pide comida de tus restaurantes favoritos, sigue tu pedido en tiempo
            real y disfruta de promociones exclusivas desde nuestra aplicación.
          </p>

          <!-- Badges oficiales -->
          <div class="flex flex-wrap items-center gap-4 mt-8">
            <a href="#" target="_blank">
              <img src="../assets/badge_googleplay_es.webp" alt="Descargar en Google Play"
                class="h-14 transition duration-300 hover:scale-105" />
            </a>

            <a href="#" target="_blank">
              <img src="../assets/badge_apple_es.webp" alt="Disponible en App Store"
                class="h-14 transition duration-300 hover:scale-105" />
            </a>
          </div>
        </div>

        <!-- Mockup del teléfono -->
        <div class="flex justify-center">
          <img src="../assets/screen_one.jpg" alt="Sabix Delivery"
            class="w-72 lg:w-80 drop-shadow-2xl animate-float rounded-xl" />
        </div>
      </div>
    </div>
  </section>
</template>