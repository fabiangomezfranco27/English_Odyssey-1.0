<template>
  <div id="app">
  <nav>
  <ul>
  <li><router-link to="/">Inicio</router-link></li>
  <li><router-link to="/opcion1">Opcion 1</router-link></li>
  <li><router-link to="/opcion2">Opcion 2</router-link></li>
  <li><router-link to="/opcion3">Opcion 3</router-link></li>
  </ul>
  </nav>
  <router-view></router-view>
  </div>
 </template>
 <script>
 export default {
  name: 'App',
 };
 </script>
 <style>
 #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin-top: 60px;
 }
 ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
li {
 margin-bottom: 10px;
}
a {
 text-decoration: none;
}
</style>