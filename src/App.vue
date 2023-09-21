<script setup>

import HelloWorld from './components/HelloWorld.vue'
import AppTitle from "./components/AppTitle.vue";
import Jumbotron from './components/Jumbotron.vue'


</script>

<template>

  <AppTitle></AppTitle>

  <HelloWorld class="my"></HelloWorld>

  <Jumbotron></Jumbotron>
 
</template>

<style>

.my {
  margin: 6rem 0;
}

</style>
