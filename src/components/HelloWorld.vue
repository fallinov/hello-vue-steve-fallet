<template>
  <div>
    <h1>{{ msg }}</h1>
    <p>test</p>
    <div>test</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: deeppink;
}
</style>
