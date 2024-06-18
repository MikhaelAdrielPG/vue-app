<script setup>
import { RouterView } from "vue-router";
import Nav from "./components/Nav.vue";
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <Nav />
  <button @click="count++">count is: {{ count }}</button>
  <main>
    <RouterView />
  </main>
</template>
