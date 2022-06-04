<script setup>
  import AppLayout from './components/AppLayout.vue';
</script>

<template>
  <app-layout class="full-heigh"/>
</template>

<style>
html, body, #app {
  height: 100%;
}

body {
  margin: 0;
}

#app {
  font-family: Monospace, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fffb00;
}

.full-height {
  height: 100%;
}
</style>
