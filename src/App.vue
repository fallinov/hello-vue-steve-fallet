<template>
  <div id="app">
    <navigation />
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
<script>
import Navigation from "@/components/Navigation";
export default {
  name: 'App',
  components: {Navigation}
}
</script>