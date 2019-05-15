<template>
  <div id="id1">
    {{regisnmsg}}
  </div>
</template>

<script>
export default {
  name: 'regsin',
  data() {
    return {
      regisnmsg: '我是注册路由信息'
    }
  }
}
</script>
<style scoped>
#id1 {
  background-color: greenyellow;
}
</style>
