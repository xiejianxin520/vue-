<template>
  <div id="app">
    {{genmsg}}
    <br>
    <router-link to="/">点我去根注册</router-link>
    <router-link :to="{name:'regsin'}">点我去注册</router-link>
    <hr>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      genmsg: '我是根组件'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 800px;
  height: 180px;
  background-color: yellowgreen;
}
</style>
