<template>
  <button
    @click="count++"
    class="px-4 py-2 font-semibold text-sm bg-blue-500 text-white rounded-md shadow-sm hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 ease-in-out delay-150 duration-300"
  >
    You clicked me {{ count }} times.
  </button>
</template>
<script setup>
  import { ref } from "vue";

  const count = ref(0);
</script>
