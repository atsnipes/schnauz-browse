<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <DogMain msg="Welcome to Your Vue.js App"/>
</template>

<script>
import DogMain from './components/DogMain.vue'

export default {
  name: 'DogMain',
  components: {
    DogMain
  }
}
</script>

<style>
#schnauz {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
