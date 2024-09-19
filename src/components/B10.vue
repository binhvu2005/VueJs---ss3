<template>
  <h1>bai 10</h1>
  <input type="text" @keyup.enter="handleGet" v-model="input">
</template>

<script setup>
import { ref } from 'vue';
const input  = ref ('')
function handleGet (key ) { 
    if (key.shiftKey) {
        alert(`${input.value}`)
        input.value = ''
    } else {
        alert("phai bam shilft va enter")
    }
}
</script>

<style>

</style>