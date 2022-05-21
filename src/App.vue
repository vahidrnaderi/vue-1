<template>
  <div id="app">
    <h1> App.vue </h1>
    <ul>
      <li v-for="i in 10" :id="`test${i}`">{{i}}</li>
    </ul>
    <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  Data (){
    const t = new Array;
  },
  // function t1(){
  //   for (const i in 10)
  //     console.log(i)
  // }
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
