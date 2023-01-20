<script>
import AppHeader from './components/AppHeader.vue';
export default {
  name: 'Dc Comics',
  components: { AppHeader }
}
</script>

<template>
  <div class="container">
    <app-header></app-header>

    <main></main>
    <footer></footer>
  </div>

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