<script setup>
import {ref} from 'vue'
const name = ref('Oscar')
const emoji = ref('😎')
const year = ref('2026')
</script>

<template>
  <header>
    <span class="text-2xl text-center">{{ emoji }}</span>
  </header>
  <main class="display-block text-center">
    <h1 class="text-blue-300 text-3xl font-bold underline">Hello {{ name }}!</h1>
    <p>I'm a simple Vue app!</p>
  </main>
  <footer class="bottom-0 fixed pb-5">
    <p class="text-blue-300 text-center">&copy; {{ year }} My Vue App. All rights reserved.</p>
  </footer>
</template>
