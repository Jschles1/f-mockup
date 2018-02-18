<template>
  <div id="app">
    <navbar></navbar>
    <intro></intro>
    <mission></mission>
    <experts></experts>
    <community></community>
    <masterclasses></masterclasses>
    <feedback></feedback>
    <benefits></benefits>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Intro from './components/Intro.vue';
import Mission from './components/Mission.vue';
import Experts from './components/Experts.vue';
import Community from './components/Community.vue';
import Masterclasses from './components/Masterclasses.vue';
import Feedback from './components/Feedback.vue';
import Benefits from './components/Benefits.vue';

export default {
  components: {
    'navbar': Navbar,
    'intro': Intro,
    'mission': Mission,
    'experts': Experts,
    'community': Community,
    'masterclasses': Masterclasses,
    'feedback': Feedback,
    'benefits': Benefits
  }
}
</script>

<style lang="scss">
  body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
  }
</style>
