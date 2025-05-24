<script setup>
import FooterSection from './components/FooterSection.vue';
import Navbar from './components/Navbar.vue';

</script>

<template>
  <Navbar />
  <router-view></router-view>
  <FooterSection />
</template>