<template>
  <header>
    <div class="container head">
      <img src="@/assets/dc-logo.png" alt="logo">
      <nav>
        <ul class="nav" >
          <li><strong><a href="#">CARACTERS</a></strong></li>
          <li><strong><a href="#">COMICS</a></strong></li>
          <li><strong><a href="#">MOVIES</a></strong></li>
          <li><strong><a href="#">TV</a></strong></li>
          <li><strong><a href="#">GAMES</a></strong></li>
          <li><strong><a href="#">COLLECTIBLES</a></strong></li>
          <li><strong><a href="#">VIDEO</a></strong></li>
          <li><strong><a href="#">FANS</a></strong></li>
          <li><strong><a href="#">NEWS</a></strong></li>
          <li><strong><a href="#">SHOP</a></strong></li>
        </ul>
      </nav>
    </div>
    <div class="sottotitolo">
      <h3>--> Content goes here</h3>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
.head{
  background-color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: nowrap;  
}
.nav{
  list-style-type: none; 
}
 ul li a{
  text-decoration: none;
  color: #1e2935;
  font-size: 11px;
}
 li{
  display: inline-block;
  margin: 0px 13px;
}
a:hover {
  color: blue;
  padding-bottom: 32px;
}
a:hover {
  color: blue;
border-bottom: 4px solid blue;
}
img{
  width: 80px;
  margin-bottom: 10px;
}
.sottotitolo{
  height: 100px;
  background-color: black;
  color: white;
  display: flex;
  align-items: center;
}
.sottotitolo h3{
  margin-left: 190px;
  font-size: 23px;
}
</style>