<script setup>
  defineProps({
    user:String
   })
</script>
<template>
    <div>
      <h1>Welcome to the About Page {{ user }}</h1>
        <p>This is the home page of your application.</p>
    </div>
 </template>      