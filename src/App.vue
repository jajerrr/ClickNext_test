<script setup>
import Zone_1 from './components/Zone_1.vue'
import Zone_2 from './components/Zone_2.vue'
import Zone_3 from './components/Zone_3.vue'
import Zone_4 from './components/Zone_4.vue'
import Zone_5 from './components/Zone_5.vue'
import Zone_6 from './components/Zone_6.vue'
import Zone_7 from './components/Zone_7.vue'
import Zone_8 from './components/Zone_8.vue'
import Zone_9 from './components/Zone_9.vue'
</script>

<template>
  <div class="scroll-container">
    <Zone_1 />
    <Zone_2 />
    <Zone_3 />
    <Zone_4 />
    <Zone_5 />
    <Zone_6 />
    <Zone_7 />
    <Zone_8 />
    <Zone_9 />
  </div>
</template>

<style scoped>
body, html {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  overflow-x: hidden; 
}

.scroll-container {
  display: flex;
  flex-direction: column;
  align-items: center; 
  overflow-y: auto; 
  width: 100vw;
  scroll-snap-type: y mandatory;
  margin: 0;
  padding: 0;
}

.zone {
  scroll-snap-align: start;
  width: 100%;
  max-width: 100vw;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
