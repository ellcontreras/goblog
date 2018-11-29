<template>
  <div id="app">
    <nav class="navbar is-light">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item">
          <h3 class="title is-3">Goblog</h3>
        </router-link>
      </div>
    </nav>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
