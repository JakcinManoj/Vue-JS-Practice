<template>
  <main>
    <div>
      <h4>Counter App</h4>
      <h1>{{ count }}</h1>
      <button @click="count++">+</button>
      <button @click="count --">-</button>
    </div>
  </main>
</template>

<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<style scoped>
main {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  widows: 100vw;
}
</style>
