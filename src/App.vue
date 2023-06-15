<template>
  <div id="app">
    <nav>
      <router-link to="/">Portada</router-link> |
      <router-link to="/about">Personajes</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
body {
  background-color: lightblue;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: blue;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: white;
}

nav a.router-link-exact-active {
  color: blue;
}
</style>
