<script setup>

</script>

<template>
  <header class="header" >
    <div class="wrapper">
    <img class="portfolio" src="@/assets/portfolio.svg" alt="" />
    <div class="info" >
      <p id="name" >ANNA COMINELLI</p>
      <p id="description">GRAPHIC DESING & DIGITAL COMMUNICATION</p>
    </div>
    </div>
  </header>
</template>

<style scoped>
.portfolio {
  max-height: 400px;
  margin-left: 27px;
  margin-bottom: 160px;

}
.header {
  height: 750px;
  margin-top:50px ;
}
.info {
margin-left: 32px;
margin-top: -150px;
}
#name {
  font-weight: 500;
  margin-bottom: -3px;
}
@media (max-width: 1100px){
.portfolio{
    width: 100%;
}
#name{
  font-size: small;
} 
#description{
  font-size: small;
} 
  }


</style>
