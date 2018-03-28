<template>
  <div class="goods">
    <div class="menu-box">
      <ul>
        <li>
          <p><span>热销榜</span></p>
        </li>
        <li><p><i class="decrease_1"></i><span>热销榜</span></p></li>
        <li><p><span>热销榜</span></p></li>
        <li><p><span>热销榜</span></p></li>
        <li><p><span>热销榜</span></p></li>
        <li><p><span>热销榜</span></p></li>
        <li><p><span>热销榜</span></p></li>
      </ul>
    </div>
    <div class="foods-box">
      <ul class="food-class">
        <li>
          <dl class="class-item">
            <dt>热销榜</dt>
            <dd class="good-item">
              <div class="img-box">
                <img src="http://fuss10.elemecdn.com/c/cd/c12745ed8a5171e13b427dbc39401jpeg.jpeg?imageView2/1/w/114/h/114">
              </div>
              <div class="info">
                <h2>皮蛋瘦肉粥</h2>
                <p class="des">
                  鸡翅350g(8只）、蛋黄50g
                </p>
                <p class="sell-info">
                  月售229份 好评率100%
                </p>
                <p class="price">
                  ￥10
                </p>
                <i class="add icon-add_circle"></i>
              </div>
            </dd>
          </dl>
        </li>
        <li>
          <dl class="class-item">
            <dt>热销榜</dt>
            <dd class="good-item">
              <div class="img-box">
                <img src="http://fuss10.elemecdn.com/c/cd/c12745ed8a5171e13b427dbc39401jpeg.jpeg?imageView2/1/w/114/h/114">
              </div>
              <div class="info">
                <h2>皮蛋瘦肉粥</h2>
                <p class="des">
                  鸡翅350g(8只）、蛋黄50g
                </p>
                <p class="sell-info">
                  月售229份 好评率100%
                </p>
                <p class="price">
                  ￥10
                </p>
                <i class="add icon-add_circle"></i>
              </div>
            </dd>
          </dl>
        </li>
        <li>
          <dl class="class-item">
            <dt>热销榜</dt>
            <dd class="good-item">
              <div class="img-box">
                <img src="http://fuss10.elemecdn.com/c/cd/c12745ed8a5171e13b427dbc39401jpeg.jpeg?imageView2/1/w/114/h/114">
              </div>
              <div class="info">
                <h2>皮蛋瘦肉粥</h2>
                <p class="des">
                  鸡翅350g(8只）、蛋黄50g
                </p>
                <p class="sell-info">
                  月售229份 好评率100%
                </p>
                <p class="price">
                  ￥10
                </p>
                <i class="add icon-add_circle"></i>
              </div>
            </dd>
          </dl>
        </li>
      </ul>
    </div>
  </div>
</template>
<script type="text/ecmascript-6">
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~@/common/stylus/mixin"
.goods
  width: 100%
  height: 100%
  display: flex
  .menu-box
    width: 80px
    background: #f3f5f7
    ul
      li
        font-size: 0
        display: table
        height: 54px
        width: calc(100% - 24px)
        line-height: 14px
        margin: 0 auto
        border-1px(rgba(7,17,27,0.1))
        p
          display: table-cell
          vertical-align: middle
          i
            display: inline-block
            width: 12px
            height: 12px
            background-size: 100% auto
            background-repeat: no-repeat
            vertical-align: middle
            margin-right: 4px
          span
            vertical-align: middle
  .foods-box
    flex: 1
    .food-class
      &>li
        .class-item
          dt
            width: 100%
            height: 26px
            line-height: 26px
            background: #f3f5f7
            color: #93999f
            padding-left: 14px
            border-left: 2px solid #d9dde1
          dd
            padding: 18px 0
            margin: 0 18px
            border-1px(rgba(7,17,27,0.1))
            display: flex
            overflow: hidden
            .img-box
              width: 57px
              height: 57px
              margin-right: 10px
              img
                display: block
                width: 100%
                height: 100%
            .info
              flex: 1
              position: relative
              width: 0
              h2
                font-size: 14px
                margin: 2px 0 8px 0
              .des
                width: 100%
                color: #93999f
                margin-bottom: 8px
                over-hide()
              .sell-info
                color: #93999f
              .price
                display: inline-block
                height: 24px
                margin-right: 8px
                font-size: 14px
                color: #f01414
                line-height: 24px
              .add
                display: inline-block
                padding: 6px
                line-height: 24px
                font-size: 24px
                color: #00a0dc
                position: absolute
                right: 0
                bottom: -8px
            &:last-child
              &:after
                content: none
// 图标公用样式
.decrease_1
  bg-image("../header/decrease_1")
.discount_1
  bg-image("../header/discount_1")
.guarantee_1
  bg-image("../header/guarantee_1")
.invoice_1
  bg-image("../header/invoice_1")
.special_1
  bg-image("../header/special_1")
</style>
