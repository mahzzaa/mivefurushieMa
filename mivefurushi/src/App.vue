<template>
  <div id="app">
    <!-- <h1>{{ msg }}</h1>
    <h2>select your fruit</h2> -->
    <!-- <mivebgirim></mivebgirim> -->
    <!-- <mivebgirim></mivebgirim> -->
    <router-view></router-view>
    <!-- <router-link to="/apple">Apple</router-link> -->
    
  </div>
</template>

<script>
import apple from './components/apple'
import mivebgirim from './components/mivebgirim'
export default {
  components:{
    'mivebgirim': mivebgirim,
    'apple': apple
  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Fruit App'
    }
  }
}
</script>

<style lang="scss">
body{
  background-color: #fff8ee;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
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

img{
  width: 25%;
}
</style>
