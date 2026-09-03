<script setup>
import { ref } from 'vue'

const message = ref('Entorno listo')
</script>

<template>
  <main>
    <p class="eyebrow">CAFETERIA</p>
    <h1>Tu café empieza aquí.</h1>
    <p>{{ message }} con Vue.js, Spring Boot y PostgreSQL.</p>
  </main>
</template>

<style>
:root { font-family: Georgia, serif; color: #30261f; background: #f4eee5; }
body { margin: 0; min-width: 320px; }
main { max-width: 760px; margin: 18vh auto; padding: 2rem; }
.eyebrow { color: #a04b2c; font: 700 .8rem/1 sans-serif; letter-spacing: .18em; }
h1 { font-size: clamp(2.8rem, 8vw, 6rem); line-height: .95; margin: 1rem 0; }
p { font-size: 1.15rem; line-height: 1.5; }
</style>