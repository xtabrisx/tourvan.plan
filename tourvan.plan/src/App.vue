<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheNavigation from './components/TheNavigation.vue';
</script>

<template>
  <TheNavigation></TheNavigation>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
    <RouterView>

    </RouterView>

      </div>
    </div>
  </div>
  <div>
  </div>
</template>

<script>
</script>
<style scoped>
</style>
