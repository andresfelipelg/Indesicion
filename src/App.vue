<template>
<!-- <img src="./assets/logo.png" alt="logo vue"> -->
<!-- <Counter :start="100" /> -->

<Indecision/>
</template>

<script>
import Indecision from './components/Indecision.vue'


export default {
  components: { Indecision
  //Counter
  },

  
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
