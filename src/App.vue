<script setup>
import Navbar from './components/Navbar.vue';
</script>

<template>
  <div>
    <Navbar />
    <main class="px-8 py-6 bg-gray-100">
      <RouterView />
    </main>
  </div>
</template>

<style scoped></style>
