<script setup lang="ts">
import Tabs from "./Tabs.vue";
import ModeViews from "./ModeViews.vue";
import Options from "./Options.vue";
</script>

<template>
  <div class="filter-list">
    <Options></Options>
    <Tabs></Tabs>
    <ModeViews></ModeViews>
  </div>
</template>

<style scoped>
.filter-list {
  display: flex;
  text-align: center;
}

@media only screen and (max-width: 780px) {
  .filter-list {
    display: block;
  }
}
</style>
