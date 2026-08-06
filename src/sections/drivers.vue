<script setup lang="ts">
import { Clock3, MapPinned, Smartphone, Wallet } from '@lucide/vue';

</script>

<template>
  <section class="py-24 px-6 bg-gray-50">
    <div class="max-w-7xl mx-auto flex flex-col lg:flex-row-reverse items-center justify-between gap-16">
      <!-- Información -->
      <div class="lg:w-1/2">
        <span class="inline-block bg-[#fa8bf5]/20 text-[#7e097e] font-semibold px-4 py-2 rounded-full mb-5">
          Únete al equipo
        </span>

        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
          Conviértete en un
          <span class="text-[#9d2a9c]">Repartidor Sabix Delivery</span>
        </h2>

        <p class="mt-6 text-gray-600 text-lg leading-8">
          Genera ingresos entregando pedidos cuando tú decidas. Sé parte de una
          comunidad que conecta comercios y clientes de forma rápida y segura.
        </p>

        <!-- Beneficios -->
        <div class="mt-10 space-y-6">
          <div class="flex items-start gap-4">
            <Wallet class="w-9 h-9 text-[#9d2a9c]" />

            <div>
              <h3 class="font-semibold text-lg text-gray-800">Gana dinero</h3>

              <p class="text-gray-600">
                Obtén ingresos por cada entrega realizada.
              </p>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <Clock3 class="w-9 h-9 text-[#9d2a9c]" />

            <div>
              <h3 class="font-semibold text-lg text-gray-800">
                Horarios flexibles
              </h3>

              <p class="text-gray-600">
                Tú decides cuándo conectarte y realizar entregas.
              </p>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <MapPinned class="w-9 h-9 text-[#9d2a9c]" />

            <div>
              <h3 class="font-semibold text-lg text-gray-800">
                Entregas cerca de ti
              </h3>

              <p class="text-gray-600">
                Recibe pedidos dentro de tu zona para optimizar tu tiempo.
              </p>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <Smartphone class="w-9 h-9 text-[#9d2a9c]" />

            <div>
              <h3 class="font-semibold text-lg text-gray-800">
                Todo desde la app
              </h3>

              <p class="text-gray-600">
                Gestiona tus pedidos y ganancias desde tu teléfono.
              </p>
            </div>
          </div>
        </div>

        <!-- Botón -->
        <button
          class="mt-10 bg-[#7e097e] hover:bg-[#9d2a9c] text-white font-semibold px-8 py-4 rounded-xl transition duration-300 shadow-lg hover:shadow-xl">
          Quiero ser repartidor
        </button>
      </div>

      <!-- Imagen -->
      <div class="lg:w-1/2 flex justify-center">
        <img src="../assets/dealer.jpg" alt="Repartidor Sabix Delivery"
          class="w-full max-w-md drop-shadow-2xl hover:scale-105 transition duration-500" />
      </div>
    </div>
  </section>
</template>
