<template>
  <!--
     css class 的命名规则 block__element--modifief
  -->
  <div class="wrapper">
    <div class="position">
      <span class="iconfont icon">&#xe62c;</span>
      北京理工大学国防科技大学
      <span class="iconfont notice">&#xe613;</span>
    </div>

    <div class="search">
      <span class="iconfont">&#xe720;</span>
      小台芒果优惠商品
    </div>

    <h3></h3>

    <div class="banner">
      <img src="../common/images/banner.jpg" />
    </div>

    <div class="icons">
      <div class="item">
        <img src="../common/images/超市.png" />
        <p class="desc">超市便利</p>
      </div>
      <div class="item">
        <img src="../common/images/菜市场.png" />
        <p class="desc">菜市场</p>
      </div>
      <div class="item">
        <img src="../common/images/水果店.png" />
        <p class="desc">水果店</p>
      </div>
      <div class="item">
        <img src="../common/images/鲜花.png" />
        <p class="desc">鲜花绿植</p>
      </div>
      <div class="item">
        <img src="../common/images/医药健康.png" />
        <p class="desc">医药健康</p>
      </div>
      <div class="item">
        <img src="../common/images/家居.png" />
        <p class="desc">家居时尚</p>
      </div>
      <div class="item">
        <img src="../common/images/蛋糕.png" />
        <p class="desc">烘培蛋糕</p>
      </div>
      <div class="item">
        <img src="../common/images/签到.png" />
        <p class="desc">签到</p>
      </div>
      <div class="item">
        <img src="../common/images/大牌免运.png" />
        <p class="desc">大牌免运</p>
      </div>
      <div class="item">
        <img src="../common/images/红包.png" />
        <p class="desc">红包套餐</p>
      </div>
    </div>

    <div class="gap"></div>

    <div class="nearby">
      <h3 class="title">附近店铺</h3>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
      <diiv class="item">
        <img src="../common/images/near.png" />
        <div class="content">
          <div class="title">沃尔玛</div>
          <div class="tags">
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
            <span class="tag">月售1万+</span>
          </div>
          <p class="highlight">VIP尊受满89元送10元优惠</p>
        </div>
      </diiv>
    </div>
  </div>

  <div class="docker">
    <div class="item item--active">
      <div class="iconfont">&#xe6df;</div>
      <p class="title">首页</p>
    </div>
    <div class="item">
      <div class="iconfont">&#xe600;</div>
      <p class="title">购物车</p>
    </div>
    <div class="item">
      <div class="iconfont">&#xe63a;</div>
      <p class="title">订单</p>
    </div>
    <div class="item">
      <div class="iconfont">&#xe61a;</div>
      <p class="title">我的</p>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return ''
  }
}
</script>

<style lang="scss">
@import "../common/style/viriables.scss";
@import "../common/style/mixins.scss";

* {
  margin: 0;
  padding: 0;
}

.wrapper {
  overflow-y: auto;
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0.5rem;
  right: 0;
  padding: 0 0.18rem 0.1rem 0.18rem;

  .position {
    color: $content-fontColor;
    position: relative;
    padding: 0.16rem 0.24rem 0.16rem 0;
    line-height: 0.22rem;
    font-size: 0.12rem;
    @include ellipsis;

    .icon {
      position: relative;
      top: 0.01rem;
      font-size: 0.16rem;
    }

    .notice {
      position: absolute;
      right: 0;
      top: 0.17rem;
      font-size: 0.16rem;
    }
  }

  .search {
    line-height: 0.32rem;
    background: #f5f5f5;
    color: #b7b7b7;
    border-radius: 0.16rem;
    font-size: 0.14rem;
    margin-bottom: 0.18rem;

    .iconfont {
      position: relative;
      top: 0.02rem;
      display: inline-block;
      padding: 0 0.02rem 0 0.16rem;
      font-size: 0.2rem;
    }
  }

  .banner {
    height: 0;
    overflow: hidden;
    padding-bottom: 25.4%;
    img {
      width: 100%;
    }
  }

  .icons {
    display: flex;
    flex-wrap: wrap;
    margin-top: 0.16rem;

    .item {
      width: 20%;
      img {
        width: 0.4rem;
        height: 0.4rem;
        margin: 0 auto;
        display: block;
      }

      .desc {
        margin: 0.06rem 0 0.16rem 0;
        text-align: center;
        color: $content-fontColor;
      }
    }
  }

  .gap {
    margin: 0 -0.18rem;
    height: 0.1rem;
    background: $content-bgColor;
  }

  .nearby {
    .title {
      margin: 0.16rem 0 0.02rem 0;
      font-size: 0.18rem;
      font-weight: normal;
      color: $content-fontColor;
    }
    .item {
      display: flex;
      img {
        margin: 0.14rem 0.1rem 0 0;
        width: 0.56rem;
        height: 0.56rem;
      }
    }
    .content {
      flex: 1;
      padding-bottom: 0.12rem;
      border-bottom: 1px solid $content-bgColor;

      .title {
        line-height: 0.22rem;
        font-size: 0.16rem;
        color: $content-fontColor;
      }
      .tags {
        margin-top: 0.08rem;
        line-height: 0.18rem;
        font-size: 0.13rem;
        color: $content-fontColor;
      }
      .tag {
        margin-right: 0.16rem;
      }
      .highlight {
        margin: 0.08rem 0 0 0;
        line-height: 0.18rem;
        font-size: 0.13rem;
        color: #e93b3b;
      }
    }
  }
}

.docker {
  color: $content-fontColor;
  display: flex;
  position: absolute;
  box-sizing: border-box;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 0.49rem;
  border-top: 0.1rem solid $content-bgColor;

  .item {
    flex: 1;
    text-align: center;

    .iconfont {
      margin: 0.07rem 0.02rem 0;
      font-size: 0.18rem;
    }
  }

  .item--active {
    color: #1fa4fc;
  }

  .title {
    font-size: 0.2rem;

    // 由于 浏览器 最小的字体 为 12px , 需要 通过  transform 的 scale 进行缩放 （将 20px 缩放 为 10px）
    transform: scale(0.5, 0.5);

    // 以那里为中心进行缩放
    transform-origin: center top;
  }
}
</style>
