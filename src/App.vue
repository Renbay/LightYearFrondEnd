<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import FooterBar from './components/FooterBar.vue';
</script>

<template>
  <div class="wrapper">
    <NavBar></NavBar>
    <main class="content">
      <!-- 主要內容 -->
      <RouterView />
    </main>
    <FooterBar></FooterBar>
  </div>
  <div >
    
  </div>
</template>

<style scoped>
</style>
