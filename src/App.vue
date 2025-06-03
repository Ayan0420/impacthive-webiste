<script setup>
import { Transition } from 'vue';
import FooterSection from './components/FooterSection.vue';
import Navbar from './components/Navbar.vue';
import { RouterView } from 'vue-router';

</script>

<template>
  <Navbar />
  <RouterView />
  <FooterSection />
</template>


<style>
/* .dissolve-enter-active,
.dissolve-leave-active {
  transition: opacity 0.2s ease-in, transform 0.2s ease-out;
}

.dissolve-enter-from,
.dissolve-leave-to {
  opacity: 0;
  transform: translateY(-50px);
} */

</style>