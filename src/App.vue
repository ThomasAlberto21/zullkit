<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/layouts/Navbar.vue'
</script>

<template>
  <div>
    <Navbar />
    <RouterView />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
