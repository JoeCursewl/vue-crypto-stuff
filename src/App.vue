<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import CardLin from './components/CardLin.vue'
import { ref } from 'vue'

const arrozito = ref(1);
</script>

<template>

  <div>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>

  <CardLin arroz={{ arrozito }}/>

  <HelloWorld msg="We're checking if that thing it's going to work"/>
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
