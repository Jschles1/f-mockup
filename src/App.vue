<template>
  <div id="app">
    <navbar></navbar>
    <intro></intro>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Intro from './components/Intro.vue';

export default {
  components: {
    'navbar': Navbar,
    'intro': Intro
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
  }
</style>
