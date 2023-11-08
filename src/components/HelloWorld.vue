<script setup>
import Jumbotron from "./Jumbotron.vue";
</script>
<script>
export default {
  name: "HelloWorld",
};
</script>

<template>
  <div>
    <Jumbotron />
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
