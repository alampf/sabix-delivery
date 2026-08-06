<script setup lang="ts">
import { Store, ShoppingBag, Truck, ChartNoAxesCombined } from '@lucide/vue';
</script>

<template>
  <section class="py-24 px-6 bg-white">
    <div
      class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-16"
    >
      <!-- Información -->
      <div class="lg:w-1/2">
        <span
          class="inline-block bg-[#fa8bf5]/20 text-[#7e097e] font-semibold px-4 py-2 rounded-full mb-5"
        >
          Crece con nosotros
        </span>

        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 leading-tight">
          Convierte tu negocio en una
          <span class="text-[#9d2a9c]">Tienda Sabix Delivery</span>
        </h2>

        <p class="mt-6 text-gray-600 text-lg leading-8">
          Miles de personas buscan nuevos lugares para ordenar todos los días.
          Únete a Sabix Delivery y aumenta tus ventas llegando a más clientes
          desde una sola plataforma.
        </p>

        <!-- Beneficios -->
        <div class="mt-10 space-y-5">
          <div class="flex items-center gap-4">
            <Store class="w-8 h-8 text-[#9d2a9c]" />
            <p>Llega a miles de clientes potenciales.</p>
          </div>

          <div class="flex items-center gap-4">
            <ShoppingBag class="w-8 h-8 text-[#9d2a9c]" />
            <p>Recibe pedidos en tiempo real.</p>
          </div>

          <div class="flex items-center gap-4">
            <Truck class="w-8 h-8 text-[#9d2a9c]" />
            <p>Entregas rápidas y seguras.</p>
          </div>

          <div class="flex items-center gap-4">
            <ChartNoAxesCombined class="w-8 h-8 text-[#9d2a9c]" />
            <p>Haz crecer tus ventas con estadísticas y reportes.</p>
          </div>
        </div>

        <!-- Botón -->
        <button
          class="mt-10 bg-[#7e097e] hover:bg-[#9d2a9c] text-white font-semibold px-8 py-4 rounded-xl transition duration-300 shadow-lg hover:shadow-xl"
        >
          Registrar mi negocio
        </button>
      </div>

      <!-- Imagen -->
      <div class="lg:w-1/2 flex justify-center">
        <img
          src="../assets/members.jpg"
          alt="Tienda Sabix Delivery"
          class="w-full h-137.5 object-cover rounded-3xl shadow-2xl hover:scale-105 transition duration-500"
        />
      </div>
    </div>
  </section>
</template>
