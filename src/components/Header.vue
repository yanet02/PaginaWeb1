<template>
    <div class="header">
      <h1>BIENVENIDO A MI CARWASH:</h1>
      <img :src="pImage" alt="Logo" class="logo" />
      <p>Tu auto limpio y reluciente, donde y cuando lo necesites. Con nuestra app, podrás registrarte fácilmente y explorar nuestros servicios:</p>
    </div>
  </template>
  
  <script setup>
  import pImage from '../assets/p.jpg';
  </script>
  
  <style scoped>
  .header {
    text-align: center;
    margin-bottom: 20px;
  }
  
  .logo {
    width: 120px;
    height: auto;
    margin-bottom: 10px;
  }
  </style>