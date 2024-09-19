<template>
    <h1>bai 8</h1>
    <div>
      <a :href="linkUrl" @click.stop.prevent="checkLink(`${linkUrl}`)">{{ linkUrl }}</a>

    </div>
  </template>
  
  <script setup>
 
      const  linkUrl= 'http://www.google.com'
     function checkLink(event) {
        if (!event.startsWith('https://')) {
            alert('Link phải bắt đầu bang https://'); 
            event.preventDefault(); 
        }else{
            window.location.href = linkUrl
        }
      }

  </script>
  
  <style scoped>

  </style>
  