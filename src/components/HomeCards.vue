<script setup>
  import { RouterLink } from 'vue-router';
  import Card from '@/components/Card.vue';
</script>

<template>
  <section class="bg-gray-400 py-4">
    <div class="container-xl lg:container m-auto">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 p-4 rounded-lg ">

      <Card>
        <h2 class="text-2xl font-bold">For Shoppers</h2>
        <p class="mt-2 mb-4"> View our product and find the one you love </p>
        <RouterLink to="/jobs" class="btn">Browse Jobs</RouterLink>
      </Card>
      <Card>
        <h2 class="text-2xl font-bold">Members / Register</h2>
        <p class="mt-2 mb-4">Charmos charmos epektos</p>
        <RouterLink to="/jobs/add" class="btn">Add Job</RouterLink>
      </Card>

      </div>
    </div>
  </section>
</template>