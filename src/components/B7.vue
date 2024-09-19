<template>
  <h1>bai 7</h1><br>
  <h2>form</h2>
  <form @submit.prevent="onSubmit">
    <input type="text">
    <button type="submit " >Submit</button>
  </form>


</template>

<script setup>
 function onSubmit (){
    alert ("Form submission prevented!")
 }
</script>

<style>

</style>