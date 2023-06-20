<script setup>

defineProps({
  title: String,
  abstract: String,
  color: String,
  imageUrl: String,
})
</script>

<template>
 <div class="custom-component" >
  <div class="title text">
    <img :src="imageUrl" alt="" class="image image-fluid">
    <h2>{{ title }}</h2> 
    <p class="abstract">
      {{ abstract }}
    </p>
  </div>
 </div>
</template>

<style scoped>
  .title {
    font-size: 1em;
    font-weight: bold;
  }
  .custom-component {
    background-color: v-bind(color);
  }

  .image {
    width: 85%;
  }
</style>
