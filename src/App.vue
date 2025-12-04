<template>
  <Header />

  <main class="p-4 min-h-[70vh]">
    <router-view />
  </main>

  <Footer />
</template>

<script setup lang="ts">
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>
