<template>
  <input
    type="text"
    v-model="inputValue"
    placeholder="Ingresa algo"
    class="bg-gray-600 text-white border-none rounded-sm h-10 w-full text-sm p-4 my-4"
  />
</template>
<script setup>
  import { ref } from "vue";

  const inputValue = ref("");
</script>
