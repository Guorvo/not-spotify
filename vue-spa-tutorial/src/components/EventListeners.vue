<!-- <script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  make this button work
  <button>count is: {{ count }}</button>
</template> -->

<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

function increment() {
  count.value++
}
</script>

<template>
  <button @click="increment">count is: {{ count }}</button>
</template>