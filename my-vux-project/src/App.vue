<template>
  <div id="app">
    <h1></h1>
    <h2>Essential Links</h2>
      <group>
        <cell title="title"></cell>
      </group>
  </div>
</template>

<script>
  import{Group, Cell} from 'vux'
export default {
      components:{
          Group,
          Cell
      },

  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

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
