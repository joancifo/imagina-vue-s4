<script setup lang="ts">
definePageMeta({
  layout: "senseiniciarsessio",
});
</script>
<template>
  <h1>Iniciar sessió</h1>
  <img src="@/assets/descarga.jpg" alt="Logo" />
  <img src="/descarga.jpg" />
  <NuxtImg src="/descarga.jpg" :placeholder="[500, 500]" height="500" />
  <form>
    <input placeholder="Usuari" />
    <input placeholder="Contrasenya" type="password" />
  </form>
</template>
