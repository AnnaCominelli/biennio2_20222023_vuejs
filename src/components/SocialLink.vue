<script setup>

</script>

<template>
 <div id="contacts" class="container text-start">
    <div class="row align-items-start">
      <div class="col-2">
        <div class="container text-start">
    <div class="row">
      <div class="col align-self-start">
        <img class="works" src="@/assets/behance.svg" alt="" />
        <p><a href="https://www.behance.net/annacominelli" class="link-dark link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover">Behance</a></p>
      </div>
      <div class="col align-self-start">
        <img class="works" src="@/assets/linkedin.svg" alt="" />
        <p><a href="https://www.linkedin.com/in/anna-cominelli-a33706239/" class="link-dark link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover">Linkedin</a></p>
      </div>
      <div class="col align-self-start">
        <img class="works" src="@/assets/instagram.svg" alt="" />
        <p><a href="https://www.instagram.com/anna_cominelli/" class="link-dark link-offset-2 link-underline-opacity-25 link-underline-opacity-100-hover">Instagram</a></p>
      </div>
    </div>
  </div>
      </div>
      <div id="form"  class="col-4">
        <form>
    <div class="mb-3">
      <label for="exampleInputEmail1" class="form-label">Name</label>
      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    </div>
    <div class="mb-3">
      <label for="exampleInputPassword1" class="form-label">Email</label>
      <input type="password" class="form-control" id="exampleInputPassword1">
    </div>
    <button type="submit" class="btn btn-primary">Contact me</button>
  </form>
      </div>
    </div>
  </div>
 
</template>

<style scoped>
#contacts {
  margin-left: 23px;
  margin-top: 50px;
  display: flex;
  flex-wrap: wrap;
}
#form {
  margin-left: 530px;
 
}
.btn {
  color: rgb(255, 255, 255);
  background-color: #FF3578;
  border-color: #ffffff;
}
#message {
  height: 20px;
}
.col {
  margin-bottom: 15px;
}
</style>
