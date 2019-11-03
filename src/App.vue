<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Creepster&display=swap');
#app {
  font-family: 'Creepster', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #086ccf;
  font-size: 5rem;
  font-weight: bold;
}
#nav {
  padding: 30px;
  font-size: 2rem;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

h1
{
  background: -webkit-linear-gradient(red,orange, yellow);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
