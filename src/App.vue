<script setup lang="ts">
import Filters from "./components/filter/Filters.vue";
import Related from "./components/related/Related.vue";
import Products from "./components/product/Products.vue";
import Tags from "./components/tag/Tags.vue";
</script>

<template>
  <div class="wrapper">
    <Filters></Filters>
    <Related></Related>
    <Products></Products>
  </div>
  <Tags></Tags>
</template>

<style scoped>
div.wrapper {
  box-shadow: 0px 1px 2px rgba(58, 58, 68, 0.24),
    0px 2px 4px rgba(90, 91, 106, 0.24);
  border-radius: 8px;
  padding: 8px 16px 16px;
  max-width: calc(100% - 6px);
}
</style>
