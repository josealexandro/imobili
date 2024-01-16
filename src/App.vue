<template>
  <TheHeader/>
  <TheBody/>
</template>

<script>
import TheHeader from './components/TheHeader.vue';
import TheBody from './components/TheBody.vue';

export default {
  name: 'App',
  components: {
    TheHeader,
    TheBody
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
}
</style>
