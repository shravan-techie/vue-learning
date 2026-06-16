<template>
  <div class="counter">
    <h2>Basic Counter</h2>
    <p>Count: {{ count }}</p>
    <button @click="count++">Increment</button>
    <button @click="count--" :disabled="count <= 0">Decrement</button>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>

<style scoped>
.counter {
  padding: 1rem;
  border: 1px solid #eaeaea;
  border-radius: 8px;
  display: inline-block;
}
button { margin-right: 0.5rem }
</style>
