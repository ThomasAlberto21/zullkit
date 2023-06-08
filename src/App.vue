<script setup>
// import { RouterLink, RouterView } from 'vue-router'
import Navbar from '@/components/Navbar.vue'
</script>

<template>
  <div>
    <Navbar />
    <!-- <RouterView /> -->
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>

<style>

</style>
