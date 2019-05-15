<template>
  <div>
    {{msgs}}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msgs: 'Welcome 我是路由组件hello'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
