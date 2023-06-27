<script setup>

</script>

<template>
<div class="row align-items-start">
    <div class="col-6">
      <div class="title" >
      Blog
    </div>
<div class="text" >
<p>
 Discovering Japan. <br>
  Be amazed by the wonders Japan can give you. <br>
 Project realized with a WordPress' template.
</p>
  <button type="button" class="btn btn-dark btn-sm">Scopri</button>
</div>
    </div>
    <div class="col">
    <img class="app" src="@/assets/blog.png" alt="">
    </div>
  </div>
</template>

<style scoped>


.app {
max-height: 400px;
margin-top: 50px;
margin-bottom: 300px;
margin-left: 30px;
}
.title {
display: flex;
justify-content: end;
font-weight: 900;
font-size: 50px;
color: #FB8700;
   
}
.text {
margin-top: 20px;
color: black;
text-align: end;
}
.col-6 {
margin-top: 135px;
margin-right: 100px;
}
.btn {
 background-color: #FB8700;
 color: white;
 margin-top: 10px;
 border-color: none;
 border: 0px; 
}

</style>
