<script setup lang="ts">

</script>


<template>

<section id="hero" class="relative min-h-screen overflow-hidden bg-white">


  <!-- Fondo degradado -->
  <div class="absolute top-0 right-0 w-[600px] h-[600px] 
              bg-gradient-to-br from-[#7E097E] via-[#BC4AB9] to-[#DB6BD7]
              rounded-full blur-3xl opacity-40">
  </div>



  <!-- Contenido -->
  <div class="relative max-w-7xl mx-auto px-6 lg:px-20 pt-20">


    <div class="grid lg:grid-cols-2 gap-12 items-center min-h-screen">


      <!-- TEXTO -->
      <div>


        <span class="
          inline-block
          bg-[#DB6BD7]/30
          text-[#7E097E]
          px-5
          py-2
          rounded-full
          font-semibold
        ">
          🚀 Entregas rápidas con Sabix
        </span>



        <h1 class="
          mt-6
          text-5xl
          lg:text-7xl
          font-bold
          leading-tight
          text-gray-900
        ">

          Todo lo que necesitas,
          
          <span class="text-[#9D2A9C]">
            hasta tu puerta
          </span>

        </h1>



        <p class="
          mt-6
          text-lg
          text-gray-600
          max-w-xl
        ">

          Sabix conecta clientes con repartidores cercanos.
          Envía productos, comida, compras y paquetes
          de forma rápida, segura y sencilla.

        </p>



        <!-- BOTONES -->
        <div class="flex flex-wrap gap-5 mt-8">


          <button class="
            bg-[#9D2A9C]
            text-white
            px-8
            py-4
            rounded-full
            font-bold
            shadow-lg
            hover:bg-[#7E097E]
            transition
          ">

            Pedir ahora 🛵

          </button>



          <button class="
            border-2
            border-[#9D2A9C]
            text-[#9D2A9C]
            px-8
            py-4
            rounded-full
            font-bold
            hover:bg-[#9D2A9C]
            hover:text-white
            transition
          ">

            Ser repartidor

          </button>


        </div>



        <!-- Datos -->
        <div class="flex gap-10 mt-12">


          <div>
            <h3 class="text-3xl font-bold text-[#7E097E]">
              +10K
            </h3>

            <p class="text-gray-500">
              Usuarios
            </p>
          </div>



          <div>

            <h3 class="text-3xl font-bold text-[#7E097E]">
              +500
            </h3>

            <p class="text-gray-500">
              Repartidores
            </p>

          </div>



          <div>

            <h3 class="text-3xl font-bold text-[#7E097E]">
              24/7
            </h3>

            <p class="text-gray-500">
              Servicio
            </p>

          </div>


        </div>


      </div>





      <!-- CELULAR TIPO APP -->
      <div class="flex justify-center">


        <div class="
          relative
          w-[330px]
          h-[650px]
          bg-black
          rounded-[45px]
          p-3
          shadow-2xl
        ">



          <div class="
            bg-white
            rounded-[35px]
            h-full
            overflow-hidden
          ">



            <!-- Header app -->

            <div class="
              bg-gradient-to-r
              from-[#9D2A9C]
              to-[#DB6BD7]
              p-6
              text-white
            ">


              <h2 class="text-2xl font-bold">
                Sabix
              </h2>


              <p>
                Tu pedido está cerca
              </p>


            </div>




            <!-- Mapa -->

            <div class="
              h-72
              bg-gray-100
              flex
              items-center
              justify-center
            ">


              <div class="
                w-28
                h-28
                bg-[#BC4AB9]
                rounded-full
                flex
                items-center
                justify-center
                text-5xl
              ">

                🛵

              </div>


            </div>





            <!-- Pedido -->

            <div class="p-6">


              <div class="
                bg-[#DB6BD7]/20
                rounded-3xl
                p-5
              ">


                <h3 class="
                  font-bold
                  text-xl
                  text-[#7E097E]
                ">

                  Pedido en camino

                </h3>



                <p class="text-gray-600 mt-2">

                  El repartidor llegará en 5 minutos

                </p>




                <div class="
                  mt-5
                  bg-[#9D2A9C]
                  text-white
                  text-center
                  py-3
                  rounded-xl
                ">

                  Ver seguimiento

                </div>


              </div>


            </div>



          </div>


        </div>


      </div>



    </div>


  </div>


</section>


</template>