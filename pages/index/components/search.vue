<template>
  <view class="search">
    <!-- 定位 -->
    <view class="location">
      <view class="iconfont icon-dizhi"></view>
      <view class="address">阿里巴巴淘宝城</view>
      <view class="iconfont icon-chevron-right"></view>
    </view>
    <!-- 搜索 -->
    <uni-easyinput class="search" prefixIcon="search" v-model="search" placeholder="搜索" @iconClick="onSearch"></uni-easyinput>
    <!-- 轮播 -->
  </view>
</template>

<script>
  export default {
    data () {
      return {
        search: ''
      }
    },
    methods: {
      onSearch () {
        console.log(this.search)
      }
    }
  }
</script>

<style lang="scss">
  .search {
    padding: 0 20rpx;
    .location {
      display: flex;
      align-items: center;
      height: 80rpx;
      line-height: 80rpx;
      .icon-dizhi {
        color: $uni-color-primary;
      }
      .address {
        margin: 0 10rpx;
        color: #333;
        font-size: 30rpx;
        font-weight: bold;
      }
      .icon-chevron-right {
        color: #333333;
      }
      .search {
        background: #eee;
      }
    }
  }
</style>
