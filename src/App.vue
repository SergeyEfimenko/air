<template>
  <div id="app">
    <Header />
    <HeroSection />
    <WhoWeAre />
    <OurExpertise />
    <FullService />
    <CreateApproach />
    <WhatPeople />
    <Contacts />
    <VisionPassionResult />
    <FormsInfo />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header';
import WhoWeAre from '@/components/WhoWeAre';
import OurExpertise from '@/components/OurExpertise';
import FullService from '@/components/FullService';
import CreateApproach from '@/components/CreateApproach';
import HeroSection from '@/components/HeroSection';
import WhatPeople from '@/components/WhatPeople';
import VisionPassionResult from '@/components/VisionPassionResult';
import FormsInfo from '@/components/FormsInfo';
import Footer from '@/components/Footer';

export default {
  name: 'App',
  components: {
    Header,
    HeroSection,
    WhoWeAre,
    OurExpertise,
    FullService,
    CreateApproach,
    WhatPeople,
    VisionPassionResult,
    FormsInfo,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
    Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif, Arial,
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000;
  background-color: #f1f9fe;
}

body {
  margin: 0;
}

* {
  box-sizing: border-box;
}
</style>
