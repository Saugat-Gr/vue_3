<script setup>
import { ref } from "vue";
let count = ref(0);

const incrementCounter = () => count.value++;
const decrementCounter = () => count.value--;

</script>

<!-- Reactivity: When data are updated the browser updates automatically: reactive() and ref() -->
<template>
  <p>{{ count }}</p>
  <button v-on:click="incrementCounter">Increment</button>
  <button v-on:click="decrementCounter">Decrement</button> 
</template>
