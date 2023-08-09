<script setup>
import { RouterView } from 'vue-router'
import NavbarHeader from './components/navbarHeader.vue';
</script>

<template>
  <NavbarHeader />

  <RouterView />
</template>

<style lang="scss">
* {
  font-family: 'Rubik', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
