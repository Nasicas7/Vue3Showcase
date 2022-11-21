<script setup lang="ts">

import HomeViewVue from './views/HomeView.vue';


let string= "Rob";

</script>

<template>

  <!-- Menu de navigation-->
  <header>
    <div class="topnav">
      <a class="active" href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </div>
  </header>


  <div class="separateur"></div>

  <div class="sBar">
    <input type="search" class="searchBar" placeholder="Search...">
  </div>

  <div class="separateur"></div>

  <div id="content">
    <div> <img src="bg.png"> </div>
    <div id="autre"> <img src="bg.png"> </div>
    <div class="separateur"></div>

  </div>


  <!-- Pied de page -->
  <footer>
    <p>
      Copyright &copy; In'dev 2022-2023 - All right Reserved
    </p>
  </footer>

</template>

<style>

* {box-sizing: border-box;}

body {
margin: 0;
font-family: Arial, Helvetica, sans-serif;

}

header {
  background-color:#282A35;
}

div#content div {
  display: inline-block;
  width: 48%;
  vertical-align: top;
  margin: 10px;
}
div#content{
  background-color: #E8E8E8;
}

.sBar {
display: flex; 
justify-content: center; 
align-items: center;
min-height: 45%;
vertical-align: top;
}


.searchBar {
width: 40%;
height: 10%;
border: 1px black solid;
border-radius: 25px;

}

.btnSearch{
padding-left: 5%;
}


.topnav {
overflow: hidden;
background-color: #e9e9e9;
}

.topnav a {
float: left;
display: block;
color: black;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-size: 17px;
}

.topnav a:hover {
background-color: #ddd;
color: black;
}

.topnav a.active {
background-color: #2196F3;
color: white;
}

.topnav input[type=text] {
float: right;
padding: 6px;
margin-top: 8px;
margin-right: 16px;
border: none;
font-size: 17px;
}

.separateur{
  width: 100%;
  height: 6%;
  background-color: black;
}

footer{
  background-color:hsla(50, 33%, 25%, .75);
}

</style>