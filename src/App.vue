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
@import url('https://fonts.googleapis.com/css?family=Raleway:400,700|Red+Hat+Display:400,700&display=swap');
body {
  font-family: 'Raleway', sans-serif;
  color: rgba(0, 0, 0, 0.8);
  font-weight: 400;
  line-height: 1.58;
  letter-spacing: -.003em;
  font-size: 20px;
}
</style>
