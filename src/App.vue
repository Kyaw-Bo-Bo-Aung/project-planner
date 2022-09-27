<script>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';

import './assets/main.css';

export default {
  components:{ NavBar }
}
</script>

<template>
  <header>
      <NavBar />
  </header>

  <RouterView />
</template>

<style scoped>

</style>
