
<template>
<div class="wrapper">
  <div class="title">
    <h1>Which is the best Framework / Library</h1>
  </div>
  <div class="container">
  <div class="react">
    <img src="../frameworks/react.png" alt="">
  </div>
  <div class="vue">
    <img src="../frameworks/vuejs.png" alt="">
  </div>
  <div class="angular">
    <img src="../frameworks/angular.png" alt="">
  </div>
</div>
</div>
</template>

<style>
.wrapper {
  text-decoration: center;
  font-family:sans-serif;
}
.title {
  margin-left: 30%;
  margin-top:5%;
}
.container {
  display: flex;
  justify-content: center;
  align-content: center;
  margin-top: 7%;
}
.react img {
  width:200px;
  height: 200px;
}
.vue img {
  width:200px;
  height: 200px;
}
.angular img {
  width:200px;
  height: 200px;
}
@media(max-width:700px) {
  .wrapper {
    text-align: center;
    margin-top:30%
  }
  .title h1{
    font-size: 15px;
    margin-left: -40%;
  }
  .container {
    margin-top: 10%;
  }
  .angular img {
    width: 100px;
    height: 100px;
  }
   .react img {
    width: 100px;
    height: 100px;
  }
   .vue img {
    width: 100px;
    height: 100px;
    
  }
}
</style>
