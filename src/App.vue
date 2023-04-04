<script setup lang="ts">
import CustomRouterView from './components/CustomRouterView.vue';

const handleDisplayModal = function () {
  console.log('DOME');
};
</script>

<template>
  <div>
    <RouterView @display-modal="handleDisplayModal"></RouterView>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
