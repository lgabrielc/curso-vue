<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>Hola h1</h1>
  <CounterTest/>
</template>

<script>
import CounterTest from './components/CounterTest'

export default {
  name: 'App',
  components: {
    CounterTest
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
