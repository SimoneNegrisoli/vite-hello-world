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
h1 {
  position: relative;
  z-index: 1000;
  font-size: 3.2em;
  line-height: 100vh;
  color: white;
}
</style>
