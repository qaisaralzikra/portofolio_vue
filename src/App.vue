<script setup>
import NavigasiBar from './components/NavigasiBar.vue';
import HeroSection from './components/HeroSection.vue';
import Experience from './components/Experience.vue';
import Tools from './components/Tools.vue';
import Service from './components/Service.vue';
import Project from './components/Project.vue';
import Testimoni from './components/Testimoni.vue';
import Contact from './components/Contact.vue';
</script>

<template>
  <header class="relative">
    <NavigasiBar/>
  </header>

  <main>
    <HeroSection/>
    <Experience/>
    <Tools/>
    <Service/>
    <Project/>
    <Testimoni/>
    <Contact/>
  </main>
</template>

<style scoped>
</style>
