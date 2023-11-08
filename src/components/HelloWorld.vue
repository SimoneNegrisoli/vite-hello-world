<script setup>
import Background from "./Background.vue";
</script>
<script>
export default {
  name: "HelloWorld",
};
</script>

<template>
  <div>
    <Background />
    <h1>Hello World</h1>
  </div>
</template>

<style scoped>
div {
  width: 100%;
  height: 100%;
  position: relative;
}
h1 {
  position: relative;
  z-index: 1000;
}
</style>
