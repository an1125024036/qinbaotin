<template>
  <div>
    <router-view></router-view>
      <van-tabbar v-model="active" active-color="#ffc000" inactive-color="#000">
        <van-tabbar-item @click="fangfa('zhong')" icon="service-o">听</van-tabbar-item>
        <van-tabbar-item @click="fangfa('home')" icon="play-circle-o">看</van-tabbar-item>
        <van-tabbar-item @click="fangfa('jian')" icon="bulb-o">讲</van-tabbar-item>
        <van-tabbar-item @click="fangfa()"  icon="point-gift-o">礼</van-tabbar-item>
        <van-tabbar-item @click="fangfa('me')"  icon="contact">我</van-tabbar-item>
      </van-tabbar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      active:"",
      wz:""
    }
  },
  methods: {
    fangfa(value){
      console.log(value);
      this.$emit('show',value)

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