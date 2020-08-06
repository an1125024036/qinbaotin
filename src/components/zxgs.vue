<template>
  <div class="time" style="margin-bottom: 35px;">
    <div class="timelot">
      <div class="nip">
        <img src="../assets/image/未标题-10.png" />&nbsp;&nbsp;
        <span>最新故事</span>
      </div>
      <div class="nip2">
        <span>
          更新&nbsp;
          <van-icon name="arrow" color="#ffb600" style="position: relative;top: 2px;" />
        </span>
      </div>
    </div>

    <div>
      <van-swipe
        :show-indicators="false"
        :loop="false"
        :width="120"
        style="padding-top: 0px;margin: 20px;"
      >
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
        <van-swipe-item style="margin: 0px 5px;">
          <img src="../assets/image/未标题-11.png" />
          <p style="color: #666666;">小塞尔采蓝莓</p>
          <span style="font-size: 13px;color: #a9a9a9;">与自然和谐相处</span>
        </van-swipe-item>
      </van-swipe>

      
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.timelot {
  margin: 40px 20px 20px 20px;
}
.timelot {
  display: flex;
}
.nip span {
  font-size: 20px;
  color: #444444;
  font-weight: bold;
}
.nip img {
  width: 35px;
  height: 35px;
  position: relative;
  top: 3px;
}
.nip {
  flex: 1;
}
.nip2 {
  padding-top: 15px;
}
.nip2 span {
  color: #ffb600;
}
.van-swipe-item img {
  width: 100%;
}
</style>