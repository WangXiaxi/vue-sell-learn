<template>
  <div class="ratings">
    <div class="ratings-top">
      <div class="score-box">
        <h2 class="score">4.2</h2>
        <div class="tit">综合评分</div>
        <div class="des">高于周边商家69.2%</div>
      </div>
      <div class="tips-box">
        <div class="tips-box-center">
          <div class="item">
            <span class="tit">服务态度</span>
            <div class="star-box">
              <div class="star star-1"></div>
              <div class="star star-2"></div>
              <div class="star star-3"></div>
              <div class="star star-4"></div>
              <div class="star star-5"></div>
            </div>
            <div class="score">4.3</div>
          </div>
          <div class="item">
            <span class="tit">商品评分</span>
            <div class="star-box">
              <div class="star star-1"></div>
              <div class="star star-2"></div>
              <div class="star star-3"></div>
              <div class="star star-4"></div>
              <div class="star star-5"></div>
            </div>
            <div class="score">4.3</div>
          </div>
          <div class="item">
            <span class="tit">商品评分</span>
            <div class="time">
              38分钟
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="split"><!-- 占位 --></div>
    <div class="rating-select">
      <div class="sift">
        <div class="btn-box border-1px">
          <a>全部23</a>
          <a>满意18</a>
          <a class="on">不满意6</a>
        </div>
        <div class="if-look">
          <i class="icon-check_circle"></i>
          <span>只看有内容的评价</span>
        </div>
      </div>
      <ul class="rating-ul">
        <li class="item">
          <div class="img-box">
            <img src="http://114.215.30.117:4200/advance.ico">
          </div>
          <div class="content">
            <h3 class="name">3**************3</h3>
            <div class="star">
              <div class="star-box"></div>
            </div>
            <div class="inner">
              不错,粥很好喝,我经常吃这一家,非常赞,以后也会常来吃,强烈推荐.
            </div>
            <div class="tips">
              <i class="icon-thumb_up"></i>
              <span class="tip">南瓜粥</span>
              <span class="tip">皮蛋瘦肉粥</span>
              <span class="tip">扁豆焖面</span>
              <span class="tip">娃娃菜炖豆腐</span>
              <span class="tip">牛肉馅饼</span>
            </div>
          </div>
        </li>
        <li class="item">
          <div class="img-box">
            <img src="http://114.215.30.117:4200/advance.ico">
          </div>
          <div class="content">
            <h3 class="name">3**************3</h3>
            <div class="star">
              <div class="star-box"></div>
            </div>
            <div class="inner">
              不错,粥很好喝,我经常吃这一家,非常赞,以后也会常来吃,强烈推荐.
            </div>
            <div class="tips">
              <i class="icon-thumb_up"></i>
              <span class="tip">南瓜粥</span>
              <span class="tip">皮蛋瘦肉粥</span>
              <span class="tip">扁豆焖面</span>
              <span class="tip">娃娃菜炖豆腐</span>
              <span class="tip">牛肉馅饼</span>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>
<script type="text/ecmascript-6">

</script>
<style lang="stylus" rel="stylesheet/stylus">
  .split
    height: 18px
    border-top: 1px solid rgba(7,17,27,0.1)
    border-bottom: 1px solid rgba(7,17,27,0.1)
    background: #f7f7f7
</style>
<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~@/common/stylus/mixin"
.ratings
  position: relative
  width: 100%
  height: 100%
  overflow: hidden
  overflow-y: scroll
  .ratings-top
    display: flex
    padding: 18px 0
    .score-box
      width: 121px
      text-align: center
      padding: 6px 0
      position: relative
      &:after
        display: block
        position: absolute
        right: 0
        top: 0
        height: 100%
        content: ' '
        border-right: 1px solid rgba(7,17,27,0.1)
      .score
        margin-bottom: 6px
        line-height: 28px
        font-size: 24px
        color: #f90
      .tit
        margin-bottom: 8px
      .des
        color: #93999f
        font-size: 10px
        line-height: 10px
    .tips-box
      flex: 1
      text-align: center
      width: 0
      padding: 6px 3px 6px 3px
      font-size: 0
      .tips-box-center
        display: inline-block
      .item
        margin-bottom: 8px
        font-size: 0
        display: flex
        .tit
          line-height: 18px
        .star-box
          margin: 0 12px
          display: flex
          justify-content: center
          align-items: center
          .star
            width: 15px
            height: 15px
            margin-right: 6px
            background: red
            &:last-child
              margin-right: 0
        .score
          line-height: 18px
          color: #f90
        .time
          line-height: 18px
          color: #93999f
          margin-left: 12px
        &:last-child
          margin-bottom: 0
  .rating-select
    width: 100%
    .sift
      padding: 18px
      border-1px(rgba(7,17,27,0.1))
      .btn-box
        width: 100%
        border-1px(rgba(7,17,27,0.1))
        padding-bottom: 18px
        font-size: 0
        a
          padding: 10px 12px
          display: inline-block
          margin-right: 6px
          font-size: 12px
          border-radius: 1px
          color: #4d555d
          background: rgba(0,160,220,0.2)
          &.on
            background: #00a0dc
            color: #fff
          &:last-child
            background: rgba(77,85,93,0.2)
            &.on
              background: #4d555d
      .if-look
        padding-top: 18px
        color: #93999f
        font-size: 0
        i
          font-size: 24px
          vertical-align: middle
          margin-right: 4px
        span
          line-height: 24px
          vertical-align: middle
    .rating-ul
      padding: 0 18px
      li.item
        display: flex
        padding: 18px 0
        border-1px(rgba(7,17,27,0.1))
        &:last-child:after
          display: none
        .img-box
          width: 28px
          height: 28px
          margin-right: 12px
          img
            width: 100%
            height: 100% 
        .content
          flex: 1
          width: 0
          .name
            margin-bottom: 4px
            line-height: 12px
            font-size: 10px
            color: #07111b
          .star
            height: 12px
            background: red
            font-size: 0
            margin-bottom: 6px
          .inner
            margin-bottom: 8px
            line-height: 18px
            color: #07111b
            font-size: 12px
          .tips
            font-size: 0
            .icon-thumb_up
              font-size: 12px
              color: #00a0dc
              margin: 0 8px 4px 0
              display: inline-block
              vertical-align: middle
            .tip
              vertical-align: middle
              margin: 0 8px 4px 0
              padding: 3px 6px
              border: 1px solid rgba(7,17,27,0.1)
              border-radius: 1px
              color: #93999f
              background: #fff
              font-size: 10px
              display: inline-block
</style>
