<template>
  <div id="app">
    <navbar></navbar>
    <intro></intro>
    <mission></mission>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Intro from './components/Intro.vue';
import Mission from './components/Mission.vue';

export default {
  components: {
    'navbar': Navbar,
    'intro': Intro,
    'mission': Mission
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
  }
</style>
