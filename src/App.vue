<template>
  <div id="app">
    <HeaderSection/>
  
    <TokenSection />
    <TokenomicsSection />
    </div>
</template>

<script>

import TokenSection from './components/TokenSection.vue';
import TokenomicsSection from './components/Tokenomics.vue';
import HeaderSection from './components/HeaderSection.vue';

export default {
  name: 'App',
  components: {
    HeaderSection,

    TokenSection,
    TokenomicsSection,
  }
}
</script>

<style>
</style>

