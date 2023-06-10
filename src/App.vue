<script setup>
import NavbarMain from './components/partials/NavbarMain.vue';
</script>

<template>
  <div class="relative bg-no-repeat bg-fixed bg-center bg-cover bg-opacity-80">
    <div class="text-white">
      <navbar-main class="sticky top-0"></navbar-main>
      <RouterView />
    </div>
  </div>
</template>

<style scoped>

</style>
