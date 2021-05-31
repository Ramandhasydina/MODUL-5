<template>
  <div id="app">
    <ul class="nav" style="backgroud-color:#e33f2fd"> 
      <li class="nav-item">
        <router-link class="nav-link" to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/About">About</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/Contact">Contact</router-link>
      </li>
    </ul>

    <router-view></router-view>

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
