<template>
  <div class="header">
    <div class="header-box">
      <div class="blur-bg"></div>
      <div class="header-info">
        <div class="image-box">
          <img src="http://fuss10.elemecdn.com/c/cd/c12745ed8a5171e13b427dbc39401jpeg.jpeg?imageView2/1/w/114/h/114">
        </div>
        <div class="text-box">
          <h2 class="tit"><i></i><span>粥品稥坊（回龙观）</span></h2>
          <p class="des">蜂鸟专送/38分钟送达</p>
          <p class="act"><i class="decrease_1"></i><span>在线支付满28减5</span></p>
        </div>
        <div class="abo-right"><span>5个</span><i class="icon-keyboard_arrow_right"></i></div>
      </div>
      <div class="header-adv"><i class="tip"></i><span>粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。</span><i class="icon-keyboard_arrow_right"></i></div>
    </div>
    <div v-show="false" class="fix-box" @touchmove.prevent>
      <div class="big-tit">粥品稥坊（回龙观）</div>
      <div class="star">
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
      </div>
      <div class="scroll-box" @touchmove.stop>
        <div class="scroll-box-s">
          <div class="sale-tit tit">优惠信息</div>
          <ul class="sale-ul">
            <li><i class="decrease_1"></i><span>在线支付满28减5</span></li>
            <li><i class="discount_1"></i><span>该商家支持发票,请下单写好发票抬头</span></li>
            <li><i class="guarantee_1"></i><span>VC无限橙果汁全场8折</span></li>
            <li><i class="invoice_1"></i><span>单人精彩套餐</span></li>
            <li><i class="special_1"></i><span>已加入“外卖保”计划,食品安全保障</span></li>
          </ul>
          <div class="adv-tit tit">商家公告</div>
          <div class="adv-content">粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。</div>
        </div>
      </div>
      <div class="close-box">
        <i class="icon-close"></i>
      </div>
    </div>
  </div>
</template>
<script type="text/ecmascript-6">

</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~@/common/stylus/mixin"
  .header
    width: 100%
    position: relative
    .header-box
      position: relative
      background: rgba(0, 0, 0, 0.5)
      color: #fff
      overflow: hidden
      .blur-bg
        position: absolute
        z-index: -1
        top: 0
        left: 0
        right: 0
        bottom: 0
        background: url('http://fuss10.elemecdn.com/c/cd/c12745ed8a5171e13b427dbc39401jpeg.jpeg?imageView2/1/w/114/h/114') center center no-repeat
        background-size: 100% auto
        filter: blur(10px)
      .header-info
        padding: 24px 12px 18px 24px
        display: flex
        position: relative
        .image-box
          width: 64px
          height: 64px
          margin-right: 16px
          img
            width: 100%
            height: 100%
        .text-box
          .tit
            font-size: 0
            margin: 2px 0 8px 0
            i
              display: inline-block
              width: 30px
              height: 18px
              bg-image("brand")
              background-size: 100% auto
              background-repeat: no-repeat
              vertical-align: middle
            span
              font-size: 16px
              font-weight: bold
              line-height: 18px
              vertical-align: middle
              margin-left: 6px
          .des
            margin-bottom: 10px
          .act
            margin-right: 30px
            over-hide()
            i
              display: inline-block
              width: 12px
              height: 12px
              background-size: 100% auto
              background-repeat: no-repeat
              vertical-align: middle
            span
              vertical-align: middle
              margin-left: 4px
        .abo-right
          position: absolute
          right: 12px
          bottom: 14px
          height: 24px
          background: rgba(0, 0, 0, 0.2)
          padding: 0 8px
          border-radius: 12px
          span
            font-size: 10px
            line-height: 24px
            vertical-align: middle
          i
            font-size: 10px
            vertical-align: middle
      .header-adv
        position: relative
        padding: 0 22px 0 12px
        height: 28px
        line-height: 28px
        background: rgba(0, 0, 0, 0.2)
        font-size: 10px
        over-hide()
        .tip
          display: inline-block
          vertical-align: middle
          width: 22px
          height: 12px
          bg-image("bulletin")
          background-size: 100% auto
          margin-right: 4px
        span
          vertical-align: middle
          font-size: 10px
        .icon-keyboard_arrow_right
          position: absolute
          right: 0
          font-size: 10px
          top: 9px
          right: 12px
    .fix-box
      position: fixed
      z-index: 1
      top: 0
      left: 0
      bottom: 0
      right: 0
      color: #fff
      background: rgba(0, 0, 0, .75)
      padding: 64px 0
      .big-tit
        font-size: 16px
        text-align: center
        font-weight: bold
      .star
        height: 24px
        margin-top: 18px
        font-size: 0
        text-align: center
        padding-top: 2px
        .item
          width: 20px
          height: 20px
          background: #fff
          display: inline-block
          margin-right: 20px
          &:last-child
            margin-right: 0
      .scroll-box
        position: absolute
        top: 140px
        bottom: 64px
        right: 10%
        left: 10%
        text-align: center
        overflow: hidden
        .scroll-box-s
          width: calc(100% + 200px)
          padding-right: 200px
          height: 100%
          overflow: hidden
          overflow-y: scroll
          -webkit-overflow-scrolling: touch
        .tit
          display: inline-block
          font-size: 14px
          padding: 0 12px
          font-weight: 700
          position: relative
          margin: 28px auto 24px auto
          &:before
            content: ''
          &:after
            content: ''
          &.sale-tit
            margin-top: 10px
        .sale-ul
          text-align: left
          li
            margin-bottom: 12px
            i
              display: inline-block
              width: 16px
              height: 16px
              background-size: 100% auto
              background-repeat: no-repeat
              vertical-align: middle
            span
              vertical-align: middle
              margin-left: 4px
        .adv-content
          text-align: left
          line-height: 2
      .close-box
        position: absolute
        width: 32px
        height: 32px
        bottom: 16px
        left: 50%
        margin-left: -16px
        text-align: center
        line-height: 32px
        i
          font-size: 32px
  // 图标公用样式
  .decrease_1
    bg-image("decrease_1")
  .discount_1
    bg-image("discount_1")
  .guarantee_1
    bg-image("guarantee_1")
  .invoice_1
    bg-image("invoice_1")
  .special_1
    bg-image("special_1")
</style>
