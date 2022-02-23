<template>
  <div id="app">
    <h1>根组件</h1>
    <router-view/>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
</style>
