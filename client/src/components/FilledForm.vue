<template>
  <div class="d-flex justify-content-around">
    <div class="">
      <div class="alert alert-success" style="margin-top: 30vh">
        felicitation pour avoir rempli le formulaire
      </div>
      <router-link :to="{ name: 'Home' }">page d'accueil</router-link>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped src="../assets/css/style.css">
</style>
