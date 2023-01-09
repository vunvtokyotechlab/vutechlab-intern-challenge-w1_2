<script setup lang="ts"></script>

<template>
  <div class="tabs-filter">
    <div class="tab-item">Show all</div>
    <div class="tab-item active">Auction</div>
    <div class="tab-item">Buy now</div>
  </div>
</template>

<style scoped>
.tabs-filter {
  color: #787885;
  display: flex;
  min-width: 256px;
  border-radius: 4px;
  background-color: #ebf2ff;
  font-size: 1.4rem;
  margin-right: 16px;
  max-height: 36px;
}

.tab-item {
  width: calc(100% / 3);
  padding: 6px 0px;
}

.tab-item:hover {
  cursor: pointer;
  color: #356ac1;
}

.active {
  color: #2264d1;
  background-color: #ffffff;
  box-shadow: 0px 1px 2px rgba(27, 78, 163, 0.24),
    0px 2px 4px rgba(41, 121, 255, 0.24);
  border-radius: 4px;
}

.active:hover {
  color: #043586;
}

@media only screen and (max-width: 1024px) {
  .tabs-filter {
    width: 100%;
    margin-top: 16px;
    margin-left: 0px;
  }
}
</style>
