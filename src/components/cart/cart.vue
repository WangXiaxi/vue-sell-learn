<template>
  <div class="cart">
    <div class="cart-box">
      <div class="ball-cart">
        <div class="inner-cart">
          <div class="tip-num">10</div>
          <i class="icon-shopping_cart"></i>
        </div>
      </div>
      <div class="price-info">
        <div class="cur-money">￥0</div>
        <div class="q-money">￥10元起送</div>
      </div>
      <div class="buy-submit">去结算</div>
    </div>
  </div>
</template>
<script type="text/ecmascript-6">
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
  .cart
    width: 100%
    height: 48px
    position: fixed
    background: #141d27
    z-index: 100
    bottom: 0
    .ball-cart
      position: absolute
      height: 56px
      width: 56px
      top: -10px
      left: 12px
      background: #141d27
      border-radius: 50%
      .inner-cart
        position: relative
        width: 44px
        height: 44px
        border-radius: 50%
        background: #2b343c
        margin: 6px auto
        text-align: center
        i
          line-height: 44px
          font-size: 24px
          color: #80858a
        .tip-num
          position: absolute
          right: -8px
          top: -6px
          padding: 0 6px
          height: 16px
          border-radius: 8px
          line-height: 16px
          color: #fff
          background: #f01414
          box-shadow: 0 4px 8px 0 rgba(0,0,0,0.4)
    .price-info
      color: #ccc
      line-height: 24px
      position: absolute
      top: 12px
      left: 80px
      font-size: 0
      color: rgba(255,255,255,0.4)
      .cur-money
        font-size: 16px
        font-weight: bold
        padding-right: 10px
        border-right: 1px solid rgba(255,255,255,0.1)
        display: inline-block
        vertical-align: middle
      .q-money
        font-size: 10px
        font-weight: bold
        padding-right: 10px
        display: inline-block
        vertical-align: middle
        margin-left: 12px
    .buy-submit
      position: absolute
      width: 105px
      right: 0
      text-align: center
      line-height: 48px
      background: #2b333b
      font-size: 12px
      font-weight: bold
      color: rgba(255,255,255,0.4)
</style>
