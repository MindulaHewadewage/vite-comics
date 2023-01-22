<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooterTop from './components/AppFooterTop.vue';
export default {
  name: 'Dc Comics',
  components: { AppHeader, AppMain, AppFooterTop }
}
</script>

<template>
  <app-header></app-header>

  <app-main></app-main>

  <app-footer-top></app-footer-top>

</template>

<style>
/* reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* generics */
img {
  max-width: 100%;
  height: auto;
}

a {
  text-decoration: none;
}

/* utils */
.container {
  margin: 0 auto;
  max-width: 1200px;
}

ul li {
  list-style-type: none;
}
</style>