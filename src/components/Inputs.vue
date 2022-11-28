<script setup>
import { ref } from "vue";
const item = ref("");
const amount = ref("");
</script>

<template>
  <div class="input-wrapper">
    <input type="text" placeholder="Enter Item" v-model="item" />
    <input type="text" placeholder="Enter Amount" v-model="amount" />
    <button>Enter Item</button>
  </div>
</template>
<style>
.input-wrapper {
  display: flex;
  justify-content: space-between;
  padding: 1rem;
}
</style>
