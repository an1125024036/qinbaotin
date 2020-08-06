<template>
  <div class="about">
  <van-swipe class="my-swipe" :autoplay="3000" indicator-color="white">
  <van-swipe-item><img src="@/assets/image/lunbo1.png"></van-swipe-item>
  <van-swipe-item><img src="@/assets/image/lunbo2.png"></van-swipe-item>
  </van-swipe>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .van-swipe {
    /* margin-top: 20px; */
    padding-top: 50px;
}
  .van-swipe__track{
    height: 173px;
  }
  .my-swipe .van-swipe-item {
    color: #fff;
    font-size: 20px;
    line-height: 150px;
    text-align: center;
  }
  .my-swipe .van-swipe-item img{
    width: 100%;
  }
</style>