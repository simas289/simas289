<template>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 <div class="container">
    <div class="top">
      <div class="logo">
      <a href="localhost:8080"><img class = "logo" src="@\assets\logo.svg" alt="site logo"></a>
      </div>
      <div class="navbar">
        <a href="">ROULETTE</a>
        <a href="">CRASH</a>
        <a href="">COINFLIPski</a>
        <div class="rightside">
        <div class="balance">
          <button>Balance: 15.45$</button>
        </div>
        <div class="profile">
          <button><img src="@\assets\profile.jpg" alt="profile picture"> SHEEEEEESH</button>
        </div>
        </div>
      </div>
    </div>
</div>
</template>

<script>
console.log("Hello everyone");
</script>

<style>
*{
  box-sizing: border-box;
}


body{
  margin: 0 0 0 0;
  background-color:#2D2B2E;
  width: 100%;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.logo{
  margin-top: 2px;
  height: 81px;
  max-width: 408px;
  padding-right: 10px;
  padding-left: 5px;
  overflow:hidden;
  float: left;
}
.logo a img{
  width: 100%;
  height: auto;
}
.top div{
  vertical-align: middle;
}

.navbar{
  background-color: #3A383B;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color:#C29947;
  padding-top: 25px;
  padding-bottom: 25px;
  padding-left: 10px;
  float: right;
}
.navbar a{
  text-decoration: none;
  color: #C29947;
  margin-right: 25px;
  font-size: 26;
  font-weight: bold;
  vertical-align: middle;
}
.balance{
  padding-left: 400px;
  padding-right: 50px;
}
.balance button{
  border-radius: 10px;
  background-color: #2D2B2E;
  border: none;
  color: white;
  padding: 20px 30px 20px 30px;
  text-align:center;
  display: inline-block;
  font-weight: bold;
  font-size: 26;
}
.profile{
  padding-right: 40px;
  padding-left: 50px;
}
.profile img{
  width: 70px;
  max-height: 90px;
  border-radius: 50px;
}
.profile button{
  border-radius: 10px;
  background-color: #2D2B2E;
  border: none;
  color: white;
  text-align:center;
  display: inline-block;
  font-weight: bold;
  font-size: 26;
  padding: 5px 5px 5px 5px;
}
.profile button img{
  vertical-align: middle;

}


</style>
