<script setup>
const counterStore = useCounterStore();
</script>

<template>
  <div class="flex items-baseline">
    <button
      class="bg-primary text-white px-4 py-2 rounded-md"
      @click="counterStore.decrement"
    >
      Decrease
    </button>
    <span class="text-lg font-bold w-10 text-center">{{
      counterStore.count
    }}</span>
    <button
      class="bg-primary text-white px-4 py-2 rounded-md"
      @click="counterStore.increment"
    >
      Increase
    </button>
  </div>
</template>
