<template>
  <div id="app">
   <Navbar/>
   <router-view />
  </div>
</template>

<script>

import Navbar from '@/components/layout/Navbar.vue'
export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style>
body{
  background: #ddd
}
</style>
