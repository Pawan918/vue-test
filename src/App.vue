<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Test msg="wait"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import { ref } from 'vue';
import Test from './components/Test.vue';
// const message = ref('');
export default {
  name: 'App',
  components: {
    // HelloWorld,
    Test,
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
