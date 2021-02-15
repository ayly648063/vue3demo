<template>
  <router-link to="/">Go to Foo</router-link>
<router-link to="/Login">Go to Foo</router-link>
 <router-view></router-view>
</template>

<script>
// import Login from './views/Login'
export default {
  name: 'App',
  components: {
    // Login
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
