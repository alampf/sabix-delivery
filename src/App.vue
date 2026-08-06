<script setup lang="ts">
import Header from './layout/header.vue';
import Hero from './sections/hero.vue';
import Services from './sections/services.vue';
import Footer from './layout/footer.vue';
import Download from './sections/download.vue';
import Members from './sections/members.vue';
import Drivers from './sections/drivers.vue';
import Cities from './sections/cities.vue';
</script>

<template>
  <div class="min-h-screen overflow-x-hidden">
    <Header />
    <main>
      <Hero />
      <Services />
      <Download />
      <Members />
      <Drivers />
      <Cities />
    </main>
    <Footer />
  </div>
</template>
