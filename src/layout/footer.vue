import { MapPin, Facebook } from '@lucide/vue';
<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
import { Mail, MapPin, Phone } from '@lucide/vue';
import {
  faFacebookF,
  faInstagram,
  faXTwitter,
} from '@fortawesome/free-brands-svg-icons';
</script>

<template>
  <footer id="contact" class="bg-[#7e097e] text-white">
    <div class="max-w-7xl mx-auto px-6 py-16">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12">
        <!-- Logo -->
        <div>
          <img src="../assets/sabix_delivery_logo.png" alt="Sabix Delivery" class="w-20 mb-5" />

          <h3 class="text-2xl font-bold">Delivery</h3>

          <p class="mt-4 text-purple-100 leading-7">
            Conectamos a las personas con sus restaurantes y negocios favoritos
            de una forma rápida, segura y confiable.
          </p>
        </div>

        <!-- Enlaces -->
        <div>
          <h4 class="text-xl font-semibold mb-5">Enlaces</h4>

          <ul class="space-y-3 text-purple-100">
            <li>
              <a href="#inicio" class="hover:text-white transition"> Inicio </a>
            </li>

            <li>
              <a href="#app" class="hover:text-white transition">
                Descargar App
              </a>
            </li>

            <li>
              <a href="#negocios" class="hover:text-white transition">
                Tiendas
              </a>
            </li>

            <li>
              <a href="#repartidores" class="hover:text-white transition">
                Repartidores
              </a>
            </li>

            <li>
              <a href="#cobertura" class="hover:text-white transition">
                Cobertura
              </a>
            </li>
          </ul>
        </div>

        <!-- Contacto -->
        <div>
          <h4 class="text-xl font-semibold mb-5">Contacto</h4>

          <div class="space-y-4 text-purple-100">
            <div class="flex items-center gap-3">
              <MapPin class="w-5 h-5" />
              <span>Tlaxcala, México</span>
            </div>

            <div class="flex items-center gap-3">
              <Phone class="w-5 h-5" />
              <span>+52 246 000 0000</span>
            </div>

            <div class="flex items-center gap-3">
              <Mail class="w-5 h-5" />
              <span>contacto@sabixdelivery.com</span>
            </div>
          </div>
        </div>

        <!-- Redes -->
        <div>
          <h4 class="text-xl font-semibold mb-5">Síguenos</h4>

          <div class="flex gap-4">
            <!-- Facebook -->
            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer"
              class="w-12 h-12 rounded-full bg-white/15 flex items-center justify-center hover:bg-white hover:text-[#1877F2] transition-all duration-300 hover:scale-110">
              <FontAwesomeIcon :icon="faFacebookF" class="text-xl" />
            </a>

            <!-- Instagram -->
            <a href="https://instagram.com" target="_blank" rel="noopener noreferrer"
              class="w-12 h-12 rounded-full bg-white/15 flex items-center justify-center hover:bg-white hover:text-[#E4405F] transition-all duration-300 hover:scale-110">
              <FontAwesomeIcon :icon="faInstagram" class="text-xl" />
            </a>

            <!-- X -->
            <a href="https://x.com" target="_blank" rel="noopener noreferrer"
              class="w-12 h-12 rounded-full bg-white/15 flex items-center justify-center hover:bg-white hover:text-black transition-all duration-300 hover:scale-110">
              <FontAwesomeIcon :icon="faXTwitter" class="text-xl" />
            </a>
          </div>

          <div class="mt-8">
            <p class="text-purple-100 mb-4">Descarga nuestra app</p>

            <div class="flex flex-col gap-3">
              <a href="https://www.apple.com/mx/app-store/" target="_blank">
                <img src="../assets/badge_apple_es.webp" alt="App Store"
                  class="h-12 w-fit hover:scale-105 transition" />
              </a>

              <a href="https://play.google.com/store/games?hl=es_MX" target="_blank">
                <img src="../assets/badge_googleplay_es.webp" alt="Google Play"
                  class="h-12 w-fit hover:scale-105 transition" />
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- Línea -->
      <div class="border-t border-white/20 mt-12 pt-8">
        <div class="flex flex-col md:flex-row items-center justify-between gap-4">
          <p class="text-purple-100 text-center md:text-left">
            © 2026 Sabix Delivery. Todos los derechos reservados.
          </p>

          <div class="flex gap-6 text-purple-100">
            <a href="#" class="hover:text-white transition">
              Aviso de privacidad
            </a>

            <a href="#" class="hover:text-white transition">
              Términos y condiciones
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
