<script>
import { RouterView } from 'vue-router';
import AboutView from './views/AboutView.vue';
import Home from './views/Home.vue'

export default {
      components: {
            Home,
            AboutView,
      }
}
</script>

<template>
      <RouterView />
      <!-- <Home />
      <AboutView /> -->
</template>