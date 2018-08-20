<template>
  <div class="main">{{ msg }}</div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'hello, vue.js!'
      }
    }
  }
</script>

<style lang="less">
  .main {
    color: red;
  }
</style>