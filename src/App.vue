<template>
  <div id="app">
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
    TokenomicsSection,
  }
}
</script>

<style>
</style>

