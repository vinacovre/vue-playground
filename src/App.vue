<template>
  <img class="main-logo" alt="Vue logo" src="./assets/todo-logo.png">
  <h1>just TODO it!</h1>
  <tab-menu></tab-menu>
</template>

<script>
import TabMenu from './components/tab-menu.vue'

export default {
  name: 'App',
  components: {
    TabMenu,
  }
}
</script>

<style>

.main-logo {
  width: 30%
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #394053;
  margin-top: 60px;
}
</style>
