<template>
  <Header title="Login"/>
  <LoinPanel />
</template>

<script>
import LoinPanel from './components/LoginPanel.vue'
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    LoinPanel,
    Header
  }
}
</script>

<style>
#app {
  background-color: rgb(184, 184, 184);
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content: center;
  height: 100vh;
  margin: 0;
  padding: 0;
}

*{
  margin: 0;
  padding: 0;
}
</style>
