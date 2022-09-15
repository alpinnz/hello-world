<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <button onclick="flutterChannel('to','nama routing')">flutterChannel('to','nama routing')</button>
    
    <button onclick="flutterChannel('string sajaaa')">flutterChannel('string sajaaa')</button>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
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
