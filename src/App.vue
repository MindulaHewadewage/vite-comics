<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';
export default {
  name: 'Dc Comics',
  components: { AppHeader, AppMain, AppFooterTop, AppFooterBottom }
}
</script>

<template>
  <app-header></app-header>

  <app-main></app-main>

  <app-footer-top></app-footer-top>

  <app-footer-bottom></app-footer-bottom>


</template>

<style lang="scss">
@use './assets/scss/style.scss';
</style>