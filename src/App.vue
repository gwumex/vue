<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
*{
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-color: black;
  /* overflow: hidden; */
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
