<template>
  <div id="app">
    <Navbar />
    <Hero/>
    <StatsSection />
    <HowItWorks />
    <InitiativeGrid />  
    <Trust />
    <BlogSlider />  
 <MetiGrid /> 
    <SiteFooter />  
    <Home />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import StatsSection from './components/StatsSection.vue';
import HowItWorks from './components/HowItWorks.vue';
import Trust from './components/Trust.vue';
import InitiativeGrid from './components/InitiativeGrid.vue';
import BlogSlider from './components/BlogSlider.vue';
import MetiGrid from './components/MetiGrid.vue';
import SiteFooter from './components/SiteFooter.vue';
</script>

<style lang="scss">
@import "./assets/styles/main.scss";
</style>
