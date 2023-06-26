<script setup>

</script>

<template>
  <div>
     <img class="works" src="@/assets/work.png" alt="" />
  </div>
<div class="row align-items-start">
    <div class="col-6">
      <div class="title" >
      Soory App
    </div>
<div class="text" >
<p>
Design System and UI Project. <br>
Soory allows you to send and receive funny apologies. <br>
Search, create and share excuses for any occasions!
</p>
  <button type="button" class="btn btn-dark btn-sm">Scopri</button>
</div>
    </div>
    <div class="col">
    <img class="app" src="@/assets/soory.png" alt="">
    </div>
  </div>
</template>

<style scoped>


.works {
max-height: 220px;
margin-left: 32px;
margin-bottom: 120px;
margin-top: -30px;
}
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
color: #7760C5;
   
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
 background-color: #7760C5;
 color: white;
 margin-top: 10px;
 border-color: none;
border: 0px; 
}
</style>
