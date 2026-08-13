<script setup lang="ts">
const menu = [
  { name: 'Inicio', href: '#hero' },
  { name: 'Servicios', href: '#services' },
  { name: 'Empresas', href: '#business' },
  { name: 'Repartidores', href: '#drivers' },
  { name: 'Ciudades', href: '#cities' },
  { name: 'Contacto', href: '#contact' },
];
</script>

<template>
  <header class="fixed top-0 left-0 right-0 z-50">
    <nav
      class="mx-auto flex max-w-7xl items-center justify-between rounded-full bg-white/90 px-8 py-4 shadow-lg backdrop-blur-md mt-5"
    >
      <!-- Logo -->
      <a href="#hero" class="flex items-center gap-3">
        <img
          src="../assets/sabix_delivery_logo_two.png"
          alt="Sabix Delivery"
          class="h-10 w-auto object-contain"
        />
      </a>

      <!-- Menú -->
      <ul class="hidden lg:flex items-center gap-8">
        <li v-for="item in menu" :key="item.name">
          <a
            :href="item.href"
            class="font-medium text-gray-700 transition hover:text-[#9D2A9C]"
          >
            {{ item.name }}
          </a>
        </li>
      </ul>

      <!-- Botones -->
      <div class="hidden lg:flex items-center gap-4">
        <button
          class="rounded-full border border-[#9D2A9C] px-6 py-2 font-semibold text-[#9D2A9C] transition hover:bg-[#9D2A9C] hover:text-white"
        >
          Iniciar sesión
        </button>

        <button
          class="rounded-full bg-[#9D2A9C] px-6 py-2 font-semibold text-white transition hover:bg-[#7E097E]"
        >
          <a href="https://play.google.com/store/games?hl=es_MX" target="_blank">Descargar App</a>
        </button>
      </div>
    </nav>
  </header>
</template>
