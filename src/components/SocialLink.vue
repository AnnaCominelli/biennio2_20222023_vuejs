<script setup>
  defineProps({
    id: Number,
    img: Image,
    name: String,
    url: String,
  })
</script>

<template>
  <div class="contacts" >
   <li> <a :href="url">{{ name }} </a></li>
  </div>
</template>

<style scoped>
.contacts {
  margin-top: 20px;
  margin-bottom: 15px;
  max-width: 30px;

}
a {
display: flex;
justify-content: start;
color: black;
font-size: large;
margin-left: 35px;
text-decoration: none;
margin-top: 15px;

}
</style>
