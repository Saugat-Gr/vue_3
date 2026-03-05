<script setup>
const myMessage = "Hello from MyComponent!";
const num = 100;

function add(x, y){
      return x + y;
}
</script>

<!--

Text Interpolation: {{ }}
Has JS expressions inside the interpolation, e.g., {{ num + 1 }} will display 101 
Only JS expressions not JS statements, e.g., {{ if (num > 100) { return 'Greater than 100' } else { return 'Less than or equal to 100' } }} is not valid and will throw an error.

-->
<template>
{{ myMessage }} - {{ num }}

<p>Adding two Numbers: 102 + 2  = {{ add(102, 2) }}</p>

</template>

<style scoped></style>
