# 01-basics — Basic Counter

A minimal Vue 3 example demonstrating a simple counter using `<script setup>`.

Usage

1. Import the component into a parent (for example `src/app/App.vue`):

```
<script setup lang="ts">
import BasicCounter from '@/learning/01-basics/BasicCounter.vue'
</script>

<template>
  <BasicCounter />
</template>
```

2. The component is intentionally small to show core concepts: template, reactivity,
   and scoped styles.
