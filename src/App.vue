<script setup lang="ts">
import Header from './layout/header.vue'
import Hero from './sections/hero.vue'
import Services from './sections/services.vue'
import Footer from './components/footer.vue'
</script>

<template>
  <div class="min-h-screen overflow-x-hidden">

    <Header />

    <main>
      <Hero />
      <Services />
    </main>

    <Footer />

  </div>
</template>