<template>
  <div class="home">
    <h1>Hello Vue 22</h1>
    <p>
      NOM : {{ nom }} {{ prenom }}
      <br>
      AGE : {{ age }}
    </p>
    <button @click="agePlus()">Anniversaire !!!</button>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Bonjour ESIG"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data() {
    return {
      prix: 200,
      age: 40,
      nom: 'Fallet',
      prenom: 'Steve'
    }
  },
  methods: {
    agePlus() {
      this.age += 1;
    }
  },
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>







