<script setup>
import Header from './Header.vue';
import Services from './Services.vue';
import LoginButtons from './LoginButtons.vue';
import Footer from './Footer.vue';

</script>

<template>
  <div class="container">
    <Header />
    <Services />
    <p><strong>Consulta precios, servicios disponibles y encuentra nuestra ubicación.</strong></p>
    <p><strong>Deja que tu auto brille con Destello Móvil</strong></p>
    <LoginButtons />
    <Footer />
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
</style>