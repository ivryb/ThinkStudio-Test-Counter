<script setup>
const counterStore = useCounterStore();
</script>
<template>
  <div>
    <h3 class="text-xl font-bold">
      Current count is: {{ counterStore.count }}
    </h3>
  </div>
</template>
