<template>
    <div>
    <img class="icon1" src="../assets/screen4.png"> 
    <img class="icon3" src="../assets/screen7.png">
    <aside>
      <center>
        <button>
        <img class="icon4" src="../assets/screen9.png">
        Iniciar sesion con Google
      </button>
      <br><br>
      <button>
        <img class="icon4" src="../assets/screen8.png">
        Iniciar sesion con Facebook
      </button>
      <br><br>
      <p>
        <b>
          ---------------  Or continue with   ---------------
        </b>
      </p>
    </center>
      <h3>
        Ususario
      </h3>
      <input type="text" placeholder="Introduzca su ususario">
      <br><br>
      <h3>
        Contraseña
      </h3>
      <input type="text" placeholder="Introduzca su contraseña">
    </aside>
    </div>
   </template>
   
   <script>
   </script>
   
   <style>
   body{
    background-image: url('../assets/screen2.png');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    color: white;
  }
  .icon1{
  height: 300px;
  width: 400px;
  position: absolute;
  bottom: 20px; left: 10px;
  border: 1px;
  }

  .icon3{
  height: 150px;
  width: 450px;
  position: absolute;
  top: 20px; right: 10px;
  border: 1px;
  }

  aside{
  position: absolute;
  top: 40%; right: 6%;
  border: 1px;
  border-radius: 20px;
  width: 300px;
  }

  button{
    box-shadow: 7px 7px 15px #3ca4bb;
    height: 30px;
    width: 260px;
    font-weight: 700;
    font-size: 16px;
  }

  .icon4{
    height: 20px;
  }

  input{
    background-color: darkgrey;
    height: 20px;
    width: 220px;
  }
 </style>