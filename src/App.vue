<script setup>
import InfoBoxes from "./components/InfoBoxes.vue";
</script>

<template>
  <div class="header">
    <h3 class="title">Income and Expense Tracker</h3>
  </div>
  <div class="boxes-wrapper">
    <div class="box">
      <InfoBoxes title="Expenses" />
    </div>

    <div class="box">
      <InfoBoxes title="Income" />
    </div>
  </div>

  <div class="disposable-income">
    <h2>Disposable Income: $0</h2>
  </div>
</template>

<style>
* {
  margin: 0px;
}
.header {
  display: flex;
  align-items: center;
  background-color: #074369;
  height: 3rem;
  color: white;
  margin: 0;
  padding: 1rem 2rem;
}

.boxes-wrapper {
  display: flex;
  justify-content: center;
  height: auto;
  width: 100%;
  margin: auto;
}

.disposable-income {
  width: 100%;
  height: auto;
  text-align: center;
}
</style>
