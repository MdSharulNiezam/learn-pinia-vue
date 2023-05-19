<template>
  <div class="about">
    <h1>About</h1>
    <h2>Two way Data Binding:</h2>
    <button 
    @click="storeCounter.increaseCount"
    class="counter-button">
      {{ storeCounter.count }}
    </button>
  </div>
</template>

<script setup>

  import { useCounterStore } from '@/stores/counter'

  const storeCounter = useCounterStore()

</script>

<style>
.about {
  text-align: center;
}

.counter-button {
  font-size: 60px;
  margin: 20px;
}

</style>
