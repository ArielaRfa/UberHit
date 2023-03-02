<template>
  <div id="app">
    <AccueilVue/>
  </div>
</template>

<script>
import AccueilVue from './page/Accueil.vue'

export default {
  name: 'App',
  components: {
    AccueilVue,
  }
}
</script>

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300:400:700&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
  padding: 20px;
}
</style>
