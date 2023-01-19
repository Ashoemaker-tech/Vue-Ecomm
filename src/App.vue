<template>
  <div id="app">
    <Header />
    <Nav />
    <router-view />
    <Footer />
  </div>
</template>

<script setup>
import Header from './Components/Header.vue'
import Nav from './Components/Nav.vue'
import Footer from './Components/Footer.vue'

</script>

<style>

</style>
