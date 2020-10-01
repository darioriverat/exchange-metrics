<template>
  <main id="app">
    <x-header></x-header>
  </main>
</template>

<script>
import XHeader from './components/XHeader';

export default {
  name: 'App',
  components: {
    XHeader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>

<style src="./assets/tailwind.css">

