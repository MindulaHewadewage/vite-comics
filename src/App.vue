<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'Dc Comics',
  components: { AppHeader, AppMain }
}
</script>

<template>
  <app-header></app-header>

  <app-main></app-main>

  <footer></footer>

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
  color: black;
  text-decoration: none;
}

/* utils */
.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>