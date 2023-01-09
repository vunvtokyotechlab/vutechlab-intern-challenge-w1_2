<script setup lang="ts">
import Tag from "./Tag.vue";
import tagList from "../../data/tag";
</script>

<template>
  <div class="tag-list">
    <Tag
      v-for="tag in tagList"
      :icon="tag.icon"
      :title="tag.title"
      :sub="tag.sub"
    ></Tag>
  </div>
</template>

<style scoped>
.tag-list {
  display: flex;
  justify-content: space-between;
  margin-top: 40px;
  flex-wrap: wrap;
}
</style>
