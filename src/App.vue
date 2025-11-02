<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://classroom.google.com" target="_blank" title="gg">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://classroom.google.com" target="_blank" title="Bet you hate google classroom">
      <img src= "./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <div>
    <h1>This is a new low</h1>
    <p><a href="/second.html" title="Go to the second page">Go to the Second Page</a></p>
  </div>
  <HelloWorld msg="Vite + Vue" />
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
a{
 padding: 10px;
}
</style>
