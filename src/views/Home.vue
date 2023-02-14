<template>
  <v-content>
    <Hero />
    <Gallery />
    <About />
   
  </v-content>
</template>

<script>
import Hero from "../components/Hero";
import Gallery from "../components/Gallery";
import About from './About.vue';


export default {
  name: "Home",

  components: {
    Hero,
    Gallery,
    About
  }
};
</script>