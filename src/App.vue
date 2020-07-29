<template>
  <!-- <h1 class="text-3xl text-red-900">Hallo World</h1> -->
  <!-- <NavBar /> -->
  <!-- <SocialButtons /> -->
  <Header id="header" class />
  <!-- <AboutMe id="aboutme" /> -->
  <Leistungen id="leistungen" />
  <Portfolio id="portfolio" />
  <Footer />
</template>

<script>
import NavBar from "./components/NavBar.vue";
// import SocialButtons from "./components/Socialbuttons.vue";
import AboutMe from "./components/AboutMePage.vue";
import Header from "./components/Header.vue";
import Leistungen from "./components/Leistungen.vue";
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    NavBar,
    Header,
    Leistungen,
    Portfolio,
    Footer,
    AboutMe,
    
  }
};
</script>
