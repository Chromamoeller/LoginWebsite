<template>
  <LoinPanel />
</template>

<script>
import LoinPanel from './components/LoginPanel.vue'

export default {
  name: 'App',
  components: {
    LoinPanel
  }
}
</script>

<style>
#app {
  /* background-color: aqua; */
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
  justify-content: center;

}
</style>
