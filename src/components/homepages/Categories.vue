<template>
  <div class="container px-4 mx-auto my-16 md:px-12">
    <h2 class="mb-4 text-xl font-medium md:mb-0 md:text-lg">Top Categories</h2>
    <div class="flex flex-wrap -mx-1 lg:-mx-4">
      <CategoriesCard title="Mobile UI Kit" :count="731" image="categories-1.jpg" />
      <CategoriesCard title="Fonts" :count="657" image="categories-2.jpg" />
      <CategoriesCard title="Icon Set" :count="83.599" image="categories-3.jpg" />
      <CategoriesCard title="Website UI Kit" :count="4.500" image="categories-4.jpg" />
    </div>
  </div>
</template>

<script>
import CategoriesCard from '../CategoriesCard.vue'

export default {
  name: 'CategoriesComponent',
  components: {
    CategoriesCard
  }
}
</script>
