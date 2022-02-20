<template>
  <div id="app">
    <router-view></router-view>
    <main-tabbar> </main-tabbar>
  </div>
</template>

<script>
import MainTabbar from './components/content/mainTabar/MainTabbar.vue'
export default {
  components: { MainTabbar }
}
</script>

<style lang="less">
@import './assets/css/base.css';
</style>
