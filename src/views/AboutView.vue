<script setup>
  import EcosystemIcon from '../components/icons/IconEcosystem.vue'
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <p>
      <i>
        <EcosystemIcon />
        Devin is super cool, everyone!
      </i>
    </p>
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
  
  p {
    margin-top: 2rem;
  }
}
</style>
