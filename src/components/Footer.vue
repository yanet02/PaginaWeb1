<template>
    <footer class="footer">
      <div class="footer-content">
        <p>&copy; 2025 Destello Móvil - Todos los derechos reservados</p>
        <p>Contáctanos: <a href="mailto:contacto@destellomovil.com">contacto@destellomovil.com</a></p>
      </div>
      <div class="footer-social">
        <a href="#" class="social-icon">Facebook</a>
        <a href="#" class="social-icon">Instagram</a>
        <a href="#" class="social-icon">Twitter</a>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #333;
    padding: 10px;
    color: white;
    text-align: center;
    font-size: 12px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .footer-content {
    margin-bottom: 5px;
  }
  
  .footer-social {
    display: flex;
    justify-content: center;
    gap: 10px;
  }
  
  .social-icon {
    color: #fff;
    text-decoration: none;
    font-size: 12px;
    transition: color 0.3s;
  }
  
  .social-icon:hover {
    color: #007BFF;
  }
  </style>
  