<template>
    <nav class="bg-blue-900 text-white shadow p-6 flex justify-between items-center">
      <div class="text-xl font-bold">Portfólio</div>
      <ul class="flex gap-6">
        <li><RouterLink to="/" class="hover:text-blue-600">Home</RouterLink></li>
        <li><RouterLink to="/about" class="hover:text-blue-600">Sobre</RouterLink></li>
        <li><RouterLink to="/contact" class="hover:text-blue-600">Contato</RouterLink></li>
      </ul>
    </nav>
  </template>
  
  <script setup>
  import { RouterLink } from 'vue-router'
  </script>