<template>
  <div id="app">
    <navbar></navbar>
    <intro></intro>
    <mission></mission>
    <experts></experts>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Intro from './components/Intro.vue';
import Mission from './components/Mission.vue';
import Experts from './components/Experts.vue';

export default {
  components: {
    'navbar': Navbar,
    'intro': Intro,
    'mission': Mission,
    'experts': Experts
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
  }
</style>
