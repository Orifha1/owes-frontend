<script setup lang="ts">

import NavBar from './components/NavBar.vue';
import SideBar from './components/SideBar.vue'
</script>

<template>


  <NavBar />
  <div class="content">
    <SideBar />
    <RouterView />
  </div>


</template>

<style scoped>
.content {
  display: flex;
}
</style>
