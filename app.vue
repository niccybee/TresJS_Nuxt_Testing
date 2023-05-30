<script setup>
import Trez from './components/Trez.client.vue';
</script>
<template>
  <div class="display-grid">
    <!-- <NuxtWelcome /> -->
    <div class="div div-1">div 1</div>
    <div class="div div-2">
      <Trez />
    </div>
  </div>
</template>
<style>
body,
body > * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.display-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  width: 100svw;
  height: 100svh;
}
.div {
  height: 100%;
  padding: 1rem;
}
.div-1 {
  background: lightgreen;
}
.div-2 {
  background: lightblue;
}
</style>
