<script setup lang="ts">
import BackButton from '../utils/BackButton.vue';

</script>

<template>
  <div class="register-message-container">
    <img src="../../assets/diabloimmortal-logo.png" alt="">
    <h1>Cuenta pendiente de aprobación</h1>
    <p class="read-the-docs">
      El usuario ya se encuentra registrado en nuestra plataforma y pendiente de aprobación. 
    </p>

    <BackButton />

    <p class="read-the-docs">Plataforma para alfombras desarrollada por <a href="https://gwerh.netlify.app"
        target="_blank">Gwerh</a>.</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.button {
  margin-bottom: .5rem;
}

</style>