<template>
  <div id="app">
    <!--<img alt="Vue logo" src="https://vuejs.org/images/logo.png" />-->
    <HelloWorld msg="Formulário de cadastro" />
    <!--<Home msg2="Segunda Página" />-->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Home from './components/Home.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Home,
  },
};
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
