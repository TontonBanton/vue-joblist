<script setup>
import Hero from '@/components/Hero.vue'
import HomeCards from '@/components/HomeCards.vue';
import homepic from '@/assets/home1.jpg'
</script>

<template>
  <div class="flex justify-center">
    <img class="h-100 w-auto" :src="homepic" alt="Vue Jobs" />
  </div>
  <Hero />
  <HomeCards/>
</template>