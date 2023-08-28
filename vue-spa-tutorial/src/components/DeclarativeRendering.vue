<!-- <script setup>
import { ref } from 'vue'

// component logic
// declare some reactive state here.
</script>

<template>
  <h1>Make me dynamic!</h1>
</template> -->

<script setup lang="ts">
import { ref, reactive } from 'vue'
const name = ref('Lucas')
const counter = reactive({
  count: 0
})
// component logic
// declare some reactive state here.
</script>

<template>
  <h1>mi nombre es {{ name.split('').reverse().join('') }}</h1>
  <p>count is: {{ counter.count }}</p>
</template>