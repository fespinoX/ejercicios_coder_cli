<template>
  <div id="app">
    <img alt="Un michi" src="./assets/michi.png">
    <HelloWorld msg="Holas vienen, holas van"/>
    <Alert alerttxt="Estás acá, esto es una alerta" />
    <Button btntxt="OHNO!" link="http://www.ohno.com.ar"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Button from './components/Button.vue'
import Alert from './components/Alert.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Button,
    Alert
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

img {
  height: 300px;
  width: auto;
}
</style>
