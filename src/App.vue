<template>
  <ViewHome msg="Welcome to Your Vue.js App"/>
</template>

<script>
import ViewHome from './components/ViewHome.vue'

export default {
  name: 'App',
  components: {
    ViewHome
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
@import './assets/css/main.css';
/* @import './assets/css/output.css'; */
</style>
