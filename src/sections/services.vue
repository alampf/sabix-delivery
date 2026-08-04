<script setup lang="ts">

const services = [
  {
    icon: "🍔",
    title: "Comida",
    description: "Recibe tus platillos favoritos rápido y seguro"
  },
  {
    icon: "📦",
    title: "Paquetes",
    description: "Envía documentos y productos a cualquier lugar"
  },
  {
    icon: "🛒",
    title: "Compras",
    description: "Nosotros compramos y entregamos por ti"
  },
  {
    icon: "💊",
    title: "Farmacia",
    description: "Medicamentos y productos hasta tu puerta"
  }
]

</script>



<template>

<section id="services" class="py-24 bg-gray-50">


  <div class="max-w-7xl mx-auto px-6 lg:px-20">


    <!-- Titulo -->

    <div class="text-center max-w-3xl mx-auto">


      <span class="
        bg-[#DB6BD7]/30
        text-[#7E097E]
        px-5
        py-2
        rounded-full
        font-semibold
      ">
        Servicios Sabix
      </span>



      <h2 class="
        mt-5
        text-4xl
        lg:text-5xl
        font-bold
        text-gray-900
      ">

        Todo lo que necesitas,
        en un solo lugar

      </h2>



      <p class="
        mt-4
        text-gray-600
      ">

        Envía, compra y recibe productos
        con nuestros repartidores cercanos.

      </p>


    </div>





    <!-- Tarjetas -->


    <div class="
      grid
      md:grid-cols-2
      lg:grid-cols-4
      gap-8
      mt-14
    ">



      <div
      v-for="service in services"
      :key="service.title"
      class="
        bg-white
        rounded-3xl
        p-8
        shadow-md
        hover:shadow-xl
        hover:-translate-y-2
        transition
      "
      >



        <div class="
          w-20
          h-20
          rounded-2xl
          bg-gradient-to-br
          from-[#BC4AB9]
          to-[#DB6BD7]
          flex
          items-center
          justify-center
          text-4xl
        ">

          {{ service.icon }}

        </div>



        <h3 class="
          mt-6
          text-2xl
          font-bold
          text-[#7E097E]
        ">

          {{ service.title }}

        </h3>



        <p class="
          mt-3
          text-gray-600
        ">

          {{ service.description }}

        </p>



      </div>



    </div>


  </div>


</section>


</template>