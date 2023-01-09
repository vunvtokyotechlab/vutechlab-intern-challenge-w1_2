<script setup lang="ts">
import Product from "./Product.vue";
import productList from "../../data/product";
</script>

<template>
  <div class="product-list">
    <Product
      v-for="(product, index) in productList"
      :title="product.title"
      :thumbnail="product.thumbnail"
      :price="product.price"
      :rate="product.rate"
      :desc="product.desc"
      :key="index"
    >
    </Product>
  </div>
</template>

<style scoped>
.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  color: #000;
  box-sizing: border-box;
}
</style>
