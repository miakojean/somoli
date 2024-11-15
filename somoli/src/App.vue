<template>
  <div id="app">
    <MyComponents /> <!-- Si tu veux aussi afficher MyComponents -->
    <Navbar /> <!-- Assure-toi que Navbar est bien référencé ici -->
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import MyComponents from './components/MyComponents.vue';
</script>
