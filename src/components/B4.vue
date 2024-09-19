<template>
    <h1>bai 4</h1>
    <div :class="{active : isActive} " :style="{color: textBlue}">block</div>
</template>

<script setup>
const isActive = true;
const textBlue = "blue";
</script>

<style>

</style>