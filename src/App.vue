<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
</script>

<template>
  <Header></Header>

  <RouterView />
</template>
<style scoped>
  * {
    margin: 0px;
    padding: 0px;
    border: none;
  }
</style>