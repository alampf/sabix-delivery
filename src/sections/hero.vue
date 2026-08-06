<script setup lang="ts">
</script>

<template>
  <section id="hero" class="relative min-h-screen overflow-hidden bg-white">
    <!-- Fondo degradado -->
    <div class="hero-gradient"></div>
    <!-- Contenido -->
    <div class="relative max-w-7xl mx-auto px-6 lg:px-20 pt-20">
      <div class="grid lg:grid-cols-2 gap-12 items-center min-h-screen">
        <!-- TEXTO -->
        <div>
          <span
            class="inline-block bg-[#DB6BD7]/30 text-[#7E097E] px-5 py-2 rounded-full font-semibold"
          >
            🚀 Entregas rápidas con Sabix
          </span>
          <h1
            class="mt-6 text-5xl lg:text-7xl font-bold leading-tight text-gray-900"
          >
            Todo lo que necesitas,
            <span class="text-[#9D2A9C]"> hasta tu puerta </span>
          </h1>
          <p class="mt-6 text-lg text-gray-600 max-w-xl">
            Sabix conecta clientes con repartidores cercanos. Envía productos,
            comida, compras y paquetes de forma rápida, segura y sencilla.
          </p>
          <!-- BOTONES -->
          <div class="flex flex-wrap gap-5 mt-8">
            <button
              class="bg-[#9D2A9C] text-white px-8 py-4 rounded-full font-bold shadow-lg hover:bg-[#7E097E] transition"
            >
              Ordenar Ahora
            </button>

            <button
              class="border-2 border-[#9D2A9C] text-[#9D2A9C] px-8 py-4 rounded-full font-bold hover:bg-[#9D2A9C] hover:text-white transition"
            >
              Ser repartidor
            </button>
          </div>
          <!-- Datos -->
          <div class="flex gap-10 mt-12">
            <div>
              <h3 class="text-3xl font-bold text-[#7E097E]">+10K</h3>
              <p class="text-gray-500">Usuarios</p>
            </div>
            <div>
              <h3 class="text-3xl font-bold text-[#7E097E]">+500</h3>
              <p class="text-gray-500">Repartidores</p>
            </div>
            <div>
              <h3 class="text-3xl font-bold text-[#7E097E]">24/7</h3>
              <p class="text-gray-500">Servicio</p>
            </div>
          </div>
        </div>
        <!-- CELULAR TIPO APP -->
        <div class="flex justify-center">
          <div
            class="relative w-82.5 h-166 bg-black rounded-[45px] p-3 shadow-2xl"
          >
            <!-- Pantalla -->
            <div class="h-full w-full overflow-hidden rounded-[35px] bg-white">
              <!-- Imagen de la aplicación -->
              <img
                src="../assets/screen_two.jpg"
                alt="Sabix Delivery App"
                class="h-full w-full object-cover"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
