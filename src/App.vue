<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="min-h-screen bg-gray-100">
    <Navbar />
    <main class="max-w-4xl mx-auto p-4 pb-24">
      <router-view></router-view>
    </main>
    <Footer />
  </div>
</template>
