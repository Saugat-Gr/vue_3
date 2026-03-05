<script setup>

  const img ={
    src: './assets/teddy.jpg',
    alt: 'Teddy Image',
    height: 500,
    width: 500
  };

</script>

<template>
        <h1>This is MyComponent Image</h1>
        <img :=img />
</template>