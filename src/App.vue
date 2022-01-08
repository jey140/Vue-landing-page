<template>
  <div id="app">
   
    <Navbar />
    <Jumbotron />
    <CTA />
    <Cards />
    <Footer />

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Jumbotron from './components/Jumbotron.vue';
import CTA from './components/CTA.vue';
import Cards from './components/Cards.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    CTA,
    Cards,
    Footer
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;


}
</style>
