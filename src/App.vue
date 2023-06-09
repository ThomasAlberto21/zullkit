<template>
 <div>
  <Navbar />
  <RouterView />
 </div>
</template>

<script>
import { RouterView } from 'vue-router'
import Navbar from './components/layouts/Navbar.vue';

export default {
 name: 'App',
 components: {
  RouterView,
  Navbar
 }
}
</script>
