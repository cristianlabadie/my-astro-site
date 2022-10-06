<template>
  <button @click="count++">You clicked me {{ count }} times.</button>
</template>
<script setup>
  import { ref } from "vue";

  const count = ref(0);
</script>

<style>
  button {
    background-color: #eee;
    border: 1px solid #ddd;
    border-radius: 3px;
    color: #333;
    cursor: pointer;
    display: inline-block;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.5;
    margin: 0;
    padding: 6px 12px;
    text-align: center;
    vertical-align: middle;
    white-space: nowrap;
  }
</style>
