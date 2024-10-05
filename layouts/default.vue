<template>
  <div class="container">
    <Header />
    <div class="main-container">
      <Sidebar />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Header from '../components/Header.vue';
import Sidebar from '../components/Sidebar.vue';
import Main from '../components/Main.vue';
import Footer from '../components/Footer.vue';
</script>

<style>
@import '../assets/css/main.css';
</style>
