<script setup>
import esImage from '../assets/es.png'; // Asegúrate de que la imagen esté en la carpeta correcta
</script>

<template>
  <div class="container">
    <h1>BIENVENIDO A:</h1>
    <img :src="esImage" alt="Logo" class="logo" />
    <p>Tu auto limpio y reluciente, donde y cuando lo necesites. Con nuestra app, podrás registrarte fácilmente y explorar nuestros servicios:</p>

    <div class="services">
      <p>🚗 Lavado Externo</p>
      <p>✨ Lavado Completo (Interior y Exterior)</p>
      <p>🌿 Aromatizante</p>
      <p>🧼 Sanitizante</p>
      <p>⚙️ Limpieza de Motor</p>
      <p>... y más.</p>
    </div>

    <p><strong>Consulta precios, servicios disponibles y encuentra nuestra ubicación.</strong></p>
    <p><strong>Deja que tu auto brille con Destello Móvil</strong></p>

    <h3>INICIA SESIÓN COMO:</h3>
    <div class="buttons">
      <button class="btn user-btn">Usuario</button>
      <button class="btn admin-btn">Administrador</button>
    </div>
  </div>
</template>

<style scoped>
.container {
  background: white;
  padding: 20px;
  margin: 20px auto;
  max-width: 600px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  text-align: center;
}

.logo {
  width: 150px;
  height: auto;
  margin-bottom: 10px;
}

.services {
  text-align: left;
  margin: 20px auto;
  max-width: 400px;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.btn {
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  transition: background 0.3s ease;
}

.user-btn {
  background-color: #007BFF;
  color: white;
}

.admin-btn {
  background-color: #28A745;
  color: white;
}

.btn:hover {
  opacity: 0.8;
}
</style>
