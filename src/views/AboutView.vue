<script setup lang="ts">
import Button from 'primevue/button';
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Button
      label="PrimeVue Button"
      severity="danger"
      size="large"
    />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}
</style>
