<template>
  <div id="app">
    <navbar></navbar>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  components: {
    'navbar': Navbar
  }
}
</script>

<style lang="scss">
  #app {
    width: 95%;
    margin: 0 auto;
  }
</style>
