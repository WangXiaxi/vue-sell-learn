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
        <div class="btn-box">
          <a>全部23</a>
          <a>全部18</a>
          <a>全部6</a>
        </div>
        <div>
          <i></i>
          <span>只看有内容的评价</span>
        </div>
      </div>
      <ul class="rating-ul">
        <li class="item">
          <div class="img-box">
            <img src="">
          </div>
          <div class="content">
            <h3 class="name">3**************3</h3>
            <div class="star">
              <div class="star-box"></div>
              <span class="star-num">30</span>
            </div>
            <div class="tips">
              <i></i>
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
<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~@/common/stylus/mixin"
.ratings
  position: relative
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
</style>
