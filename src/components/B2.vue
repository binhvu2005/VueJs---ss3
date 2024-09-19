<template>
    <div>
        <h1>bai 2
        </h1>
      <h1 :id="elementId" :class="elementClass">
        Nội dung của phần tử với id và class được ràng buộc
      </h1>
    </div>
  </template>
  
  <script setup>
       const elementId = 'my-element-id'   
       const elementClass= 'my-element-class'
  </script>
  
  <style scoped>
  .my-element-class {
    color: blue;
    font-weight: bold;
  }
  </style>
  