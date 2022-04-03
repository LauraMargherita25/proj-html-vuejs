<template>
  <div id="app">
    <header-file />
    <main-file />
    <footer-file />
  </div>
</template>

<script>
import HeaderFile from './components/HeaderFile.vue';
import MainFile from './components/MainFile.vue';
import FooterFile from './components/FooterFile.vue';

export default {
  name: 'App',
  components: {
    HeaderFile,
    MainFile,
    FooterFile,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "./assets/styles/style.scss";

#app {
  font-family: 'Montserrat', sans-serif;
}
</style>
