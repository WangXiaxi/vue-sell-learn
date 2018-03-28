<template>
  <div id="app">
    <div class="header-box">
      <v-header></v-header>
    </div>
    <div class="tab border-1px">
      <div class="tab-item">
        <router-link :to="{path:'/goods'}">商品</router-link>
      </div>
      <div class="tab-item">
        <router-link :to="{path:'/ratings'}">评论</router-link>
      </div>
      <div class="tab-item">
        <router-link :to="{path:'/seller'}">商家</router-link>
      </div>
    </div>
    <div class="view-box">
      <router-view></router-view>
    </div>
    <div class="cart-box" v-if="$route.meta.showCart">
      <v-cart></v-cart>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
import vHeader from '@/components/header/header'
import vCart from '@/components/cart/cart'
export default {
  name: 'App',
  components: {
    vHeader,
    vCart
  },
  mounted () {
    console.log(this.$route.meta.showCart)
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus">
  html,body
    height: 100%
    width: 100%
</style>
<style lang="stylus" scoped rel="stylesheet/stylus">
  @import "./common/stylus/mixin.styl"
  #app
    display: flex
    width: 100%
    height: 100%
    position: relative
    flex-direction: column
    .header-box
      position: relative
  .tab
    display: flex
    width: 100%
    height: 40px
    line-height: 40px
    // border-bottom: 1px solid rgba(7, 17, 27, 0.1)
    border-1px(rgba(7, 17, 27, 0.1))
    .tab-item
      flex: 1
      text-align: center
      & > a
        display: block
        font-size: 14px
        color: rgb(77, 85, 93)
        &.active
          color: rgb(240, 20, 20)
  .view-box
    flex: 1
    position: relative
    overflow: hidden
  .cart-box
    height: 48px
</style>
