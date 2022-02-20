<template>
  <div id="home">
    <nav-bar class="home-nav">
      <div slot="center">商品</div>
    </nav-bar>
  </div>
</template>

<script>
import navBar from '../../components/common/navbar/navBar.vue'
export default {
  components: { navBar }
}
</script>
<style lang="less" scoped>
#home {
  .home-nav {
    background-color: var(--color-tint);
    color: #fff;
  }
}
</style>
