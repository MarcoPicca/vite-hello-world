<script setup>


defineProps({
  title: '',
  subTitle: '',
})


</script>

<template>
  <h1>{{ title }}</h1>

  <div class="card">
    
    <img src="../../public/vite.svg" alt="">
  </div>

  <h2>{{ subTitle }}</h2>
  
</template>

<style scoped>

</style>
