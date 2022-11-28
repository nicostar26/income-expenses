<script setup>
import Inputs from "./Inputs.vue";
import InfoItem from "./InfoItem.vue";

defineProps({
  title: {
    type: String,
    required: true,
  },
});
</script>
<template>
  <div class="info-box-wrapper">
    <h2 class="title">{{ title }}</h2>
    <div class="info-input">
      <Inputs />
    </div>
    <div class="info-list"><InfoItem /></div>
  </div>
</template>
<style>
.title {
  margin: 0 1rem;
  color: #074369;
}
.info-box-wrapper {
  width: 35rem;
  height: auto;
  border: #074369 0.1rem solid;
  border-radius: 0.5rem;
  margin: 2rem;
  box-shadow: 10px 5px 5px #074369;
}
.info-list {
  margin: 0 1rem;
}
</style>
