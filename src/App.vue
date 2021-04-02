<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/worlds">Mundos</router-link> | 
      <router-link to="/addons">Addons</router-link> | 
      <router-link to="/config">Configurações</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
body {
  background:#EEE;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
