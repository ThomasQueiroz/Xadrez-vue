<script setup>
import Header from './components/Header.vue';
import Intro from './components/Intro.vue';
import History from './components/History.vue';
import Rules from './components/Rules.vue';
import Pieces from './components/Pieces.vue';
import Strategies from './components/Strategies.vue';
import Quote from './components/Quote.vue';
import Players from './components/Players.vue';
import Tournaments from './components/Tournaments.vue';
import Resources from './components/Resources.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <div>
    <Header />
    <Intro />
    <div class="grid-container">
      <History />
      <Rules />
      <Pieces />
    </div>
    <Strategies />
    <Quote />
    <Players />
    <Tournaments />
    <Resources />
    <Footer />
  </div>
</template>

<style scoped>

</style>