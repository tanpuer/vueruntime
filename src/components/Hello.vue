<template>
  <panel class="hello">
    <h1>{{ msg }}</h1>
    <world></world>
  </panel>
</template>

<script>
  import World from './World.vue';
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Hello World'
    }
  },
  components: {
      World
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
