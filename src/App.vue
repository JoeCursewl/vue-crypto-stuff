<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>

  <div>
    <a href="https://anthony.breadriuss.store" target="_blank">
      <img src="/brd-static/logo_recortado.png" class="logo vue" alt="Vue logo" />
    </a>
  </div>


  <HelloWorld msg="Ya termine de corregir todo lo de mi cv, ahora estoy practicando pruebas técnicas 🎉."/>
</template>

<style scoped>
.logo {
  height: 3em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #a56febaa);
}
</style>
