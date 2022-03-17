<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <TheHeader :title="pageHeader"  />
  
 
  <TheFooter />
</template>

<script setup>
import TheHeader from './components/TheHeader.vue';

import TheFooter from './components/TheFooter.vue';
const pageHeader = 'home page!';




</script>


