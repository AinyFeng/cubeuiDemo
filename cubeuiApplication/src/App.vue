<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="stylus">
    @import './common/stylus/mixin.styl'
html, body, #app
  height: 100%
  text-align: center
#app
  background-color: color-grey;
</style>
