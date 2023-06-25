<template>
  <div id="app">
  <nav>
  <ul class="icon">
  <li class="icon-li">
    <img class="icon2" src="./assets/screen6.png"> 
  <ul class="list-down">
    <li><router-link to="/">Inicio</router-link></li>
    <li><router-link to="/opcion1">Start Adventure</router-link></li>
    <li><router-link to="/opcion2">Aventura 1</router-link></li>
    <li><router-link to="/opcion3">Aventura 2</router-link></li>
  </ul>
</li>
  </ul>
  </nav>
  <router-view/>
  </div>
 </template>

 <style> 
 .icon {
  display: flex;
  gap: 1rem;
  list-style: none;
}

.icon li {
  right: 50px;
  padding: 0.5rem 1rem;
  position: relative;
  list-style: none;
}

.icon-li:hover .list-down {
  display: block;
}

.list-down {
  display: none;
  position: absolute;
}

.list-down > li{
  margin: 10px;
  background-color: white;
  text-align: center ;
  width: 100px;
  font-size: 13px ;
  box-shadow: 7px 7px 15px #3ca4bb ;
  border-radius: 30px ; 
}

a {
 text-decoration: none;
 color: black;
}
a:visited{
  color: black;
}

.icon2{
  width: 50px;
  height: 50px;
}
</style>