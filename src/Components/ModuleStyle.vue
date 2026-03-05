<template>
  <h1 v-bind:class="$style['m-class']">Module Styling with $ syntax (Kebab-Case)</h1>
  <h1 :class="$style['anotherClass']">Using Module with $ syntax with Camel Case Notation</h1>
</template>

<!-- You can define a name for the module too and they will be available as properties on the $style object not $style[] but youName.property -->
<style module>
/* Kebab-Case */

.m-class {
  background: firebrick;
}

.anotherClass{
     background-color: cyan;
     color: black;  
}
</style>
