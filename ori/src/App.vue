<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <div>
      hello
    </div>
    <button @click="btn()">click</button>
  </div>
</template>

<script>

import apple from './assets/test.js';
alert(apple)


export default {
  name: 'App',
  data() {
    return{

    }
  },
  methods: {
    btn(){
      alert("alter")
    }
  },
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
