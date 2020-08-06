<template>
  <div>
      <van-tabbar v-model="active" active-color="#ffc000" inactive-color="#000">
        <van-tabbar-item replace  to="#/" icon="service-o">标签</van-tabbar-item>
        <van-tabbar-item replace  to="#/#" icon="play-circle-o">标签</van-tabbar-item>
        <van-tabbar-item replace  to="#/#/#" icon="bulb-o">标签</van-tabbar-item>
        <van-tabbar-item replace  to="#/#/#/#" icon="point-gift-o">标签</van-tabbar-item>
        <van-tabbar-item replace  to="#/#/#/#/#" icon="contact">标签</van-tabbar-item>
      </van-tabbar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      active:""
    }
  },
};
</script>

<style>
/* .bottom{
        width: 100%;
        height: 65px;
        border-top: 1px solid #dcdcdc;
        position: fixed;
        background: #ffffff;
        top: 670px;
    } */
/* .bottom-nr {
  display: flex;
}
.bottom-dh {
  flex: 1;
  text-align: center;
  margin: 5px 0px;
}
.bottom-dh p {
  text-align: center;
  color: #999999;
} */
</style>