<template>
    <transition name="component-fade" mode="out-in">
      <router-view></router-view>
   </transition>
</template>

<script>
export default {
  name: 'App'
}  
</script>

<style lang='less'>
@import '~vux/src/styles/reset.less';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
