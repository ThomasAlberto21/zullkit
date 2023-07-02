<script setup>
import Hero from '../components/homepages/Hero.vue'
import Categories from '../components/homepages/Categories.vue'
import Items from '../components/homepages/Items.vue'
</script>

<template>
  <main>
    <Hero />
    <Categories />

    <Items />
  </main>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>
