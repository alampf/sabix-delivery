<script setup lang="ts">
import order from '../assets/order.webp';
import orderTwo from '../assets/order_two.webp';
import orderThree from '../assets/order_three.png';
const services = [
  {
    image: order,
    title: 'Ordena en tus restaurantes favoritos',
    description:
      'En Sabix Delivery encontrarás una gran variedad de restaurantes y platillos. Todo a unos cuantos clics de distancia.',
  },
  {
    image: orderTwo,
    title: 'Ordena sin complicaciones',
    description:
      '¿Se te antoja una pizza o un buen sushi? Con Sabix Delivery puedes pagar con tarjeta o efectivo y recibir tu comida donde estés.',
  },
  {
    image: orderThree,
    title: 'Entregas rápidas',
    description:
      'Nuestros repartidores priorizan la rapidez y el cuidado de cada pedido para que llegue en las mejores condiciones.',
  },
];
</script>

<template>
  <section id="services" class="py-24 bg-gray-50">
    <!-- Contenedor -->
    <div class="max-w-7xl mx-auto px-6 lg:px-8">
      <!-- Grid -->
      <div
        class="grid gap-8 justify-items-center md:grid-cols-2 lg:grid-cols-3"
      >
        <div
          v-for="service in services"
          :key="service.title"
          class="w-full max-w-sm bg-white rounded-3xl overflow-hidden shadow-md hover:shadow-xl hover:-translate-y-2 transition duration-300"
        >
          <!-- Imagen -->
          <img
            :src="service.image"
            :alt="service.title"
            class="w-full h-64 object-cover"
          />

          <!-- Contenido -->
          <div class="p-8">
            <h3 class="text-2xl font-bold text-[#7E097E]">
              {{ service.title }}
            </h3>

            <p class="mt-4 text-gray-600 leading-7">
              {{ service.description }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
