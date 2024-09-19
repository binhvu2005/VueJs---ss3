<template>
  <h1>bai 9</h1>
  <h1>count : {{count}}</h1>
  <button @click="hanldeClick">click</button>
</template>

<script setup>
import { ref } from 'vue';
const count = ref(0)
const hanldeClick =() =>{
    count.value++
   
  
}
</script>

<style>

</style>