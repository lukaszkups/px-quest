<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="game-wrapper">
    <div class="bg"></div>
  </div>
</template>

<style scoped>
.game-wrapper {
  display: block;
  position: fixed;
  overflow: hidden;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
.bg {
  position: absolute;
  width: 4024px;
  height: 3468px;
  display: block;
  background: url('./map.jpeg');
  transform: rotate(25deg) skew(-35deg, 0deg);
}
</style>
