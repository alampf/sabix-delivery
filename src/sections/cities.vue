<script setup lang="ts">
import { MapPin } from '@lucide/vue';

const cities = [
  { name: 'Tlaxcala', status: 'Disponible' },
  { name: 'Huamantla', status: 'Disponible' },
  { name: 'Terrenate', status: 'Disponible' },
  { name: 'Apizaco', status: 'Disponible' },
  { name: 'Santa Ana, Chiautempan', status: 'Proximamente' },
  { name: 'Ixtenco', status: 'Proximamente' },
  { name: 'San José Xicohténcatl', status: 'Proximanete' },
];
</script>

<template>
  <section class="py-24 px-6 bg-white">
    <div class="max-w-7xl mx-auto">
      <!-- Encabezado -->
      <div class="text-center">
        <span
          class="inline-block bg-[#fa8bf5]/20 text-[#7e097e] font-semibold px-4 py-2 rounded-full"
        >
          Cobertura
        </span>

        <h2 class="mt-6 text-4xl md:text-5xl font-bold text-gray-900">
          Estamos disponibles en
        </h2>

        <p class="mt-5 text-lg text-gray-600 max-w-3xl mx-auto">
          Comenzamos nuestra aventura en Tlaxcala y seguimos trabajando para
          llevar Sabix Delivery a más ciudades muy pronto.
        </p>
      </div>

      <!-- Ciudades -->
      <div class="mt-16 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
        <div
          v-for="city in cities"
          :key="city.name"
          class="bg-linear-to-r from-[#7e097e] via-[#9d2a9c] to-[#bc4ab9] rounded-3xl p-8 text-white shadow-2xl hover:scale-105 hover:shadow-purple-300/50 transition duration-300"
        >
          <div class="flex flex-col items-center text-center">
            <div
              class="w-16 h-16 rounded-full bg-white/20 flex items-center justify-center mb-5"
            >
              <MapPin class="w-8 h-8" />
            </div>

            <h3 class="text-2xl font-bold">
              {{ city.name }}
            </h3>

            <p
              class="mt-2 font-medium"
              :class="
                city.status === 'Disponible'
                  ? 'text-green-200'
                  : 'text-purple-100'
              "
            >
              {{ city.status }}
            </p>
          </div>
        </div>
      </div>

      <!-- Próximamente -->
      <div class="mt-16 text-center">
        <p class="text-gray-500 text-lg">
          🚀 Muy pronto llegaremos a más ciudades.
        </p>
      </div>
    </div>
  </section>
</template>
