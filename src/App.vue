<template>
 <loginComponent/>
</template>

<script>
 import loginComponent from './components/loginComponent'

export default {
  name: 'App',
  components: {
    loginComponent,
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
