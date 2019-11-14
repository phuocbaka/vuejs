<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>


<script>
export default {
  name: 'App',
  name: 'Menu'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
}
#app img{
  width: 4%;
  margin-top: -3%;
}
body, html {
  height: 100%;
  margin: 0;

}
</style>
