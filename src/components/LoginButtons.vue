<template>
  <div class="login-section">
    <h3>INICIA SESIÓN COMO:</h3>
    <div class="buttons">
      <button class="btn user-btn">Usuario</button>
      <button class="btn admin-btn">Administrador</button>
    </div>
  </div>
</template>

<style scoped>
.login-section {
  text-align: center;
  margin-top: 20px;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 10px;
}

.btn {
  padding: 10px 15px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 14px;
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
