<template>
  <div class="me">
      <div class="me-dl">
        <div class="me-xiaox">
          <img src="../assets/image/image4/未标题-2.png">
        </div>
        <div class="me-name" @click="admin()">
          <img src="../assets/image/image4/未标题-1.png">
        </div>
      </div>

      <div class="me-gn">
        <div class="me-gnan1">
          <img src="../assets/image/image4/未标题-4.png">
          <p>最近播放</p>
        </div>
        <div class="me-gnan1">
          <img src="../assets/image/image4/未标题-5.png">
          <p>我的收藏</p>
        </div>
        <div class="me-gnan1">
          <img src="../assets/image/image4/未标题-6.png">
          <p>我的购买</p>
        </div>
        <div class="me-gnan1">
          <img src="../assets/image/image4/未标题-7.png">
          <p>我的作品</p>
        </div>
      </div>

      <div class="me-tuo">
        <div class="me-tuo1">
          <img src="../assets/image/image4/x1.png">
          <span>宝贝成就卡</span>
        </div>
        <div class="me-tuo2">
          <span>点击查看</span><van-icon name="arrow" style="position: relative;top: 2px;" color="#ffffff" />
        </div>
      </div>

      <div class="me-lpdh">
        <div class="me-lpdh1" style="margin: 20px 5px 0px 22px;">
          <img src="../assets/image/image4/未标题-8.png">
        </div>
        <div class="me-lpdh1" style="margin: 20px 22px 0px 5px;">
          <img src="../assets/image/image4/未标题-9.png">
        </div>
      </div>

      <div class="me-lianj">
        <van-cell class="wwt1" title="我的宝豆" icon="like-o" style="padding: 10px 22px;color: #666666;" value="充值 >"/>
        <van-cell class="wwt2" title="我的兑换" icon="point-gift-o" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="鼓励一下" icon="star-o" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="兑换码" icon="coupon-o" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="我要提现" icon="balance-pay" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="常见问题与反馈" icon="question-o" style="padding: 10px 22px;color: #666666;" value=">"/>    
        <van-cell class="wwt2" title="联系客服" icon="phone-o" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="设置" icon="setting-o" style="padding: 10px 22px;color: #666666;" value=">"/>
        <van-cell class="wwt2" title="用户协议与隐私政策" icon="smile-comment-o" style="padding: 10px 22px;color: #666666;" value=">"/>  
      </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      
    }
  },
  methods: {
    admin(){
      this.$router.push('/index')
    }
  },
}
</script>

<style>
  .me-dl{
    width: 100%;
    height: 250px;
    background: #ffc900;
  }
  .me-xiaox img{
    width: 25px;
    height: 25px;
    float: right;
    margin: 15px 15px 0px 0px;
  }
  .me-name img{
    width: 100px;
  }
  .me-name {
    position: absolute;
    left: 40%;
    margin-top: 50px;
  }
  .me-gn{
    width: 90%;
    height: 100px;
    box-shadow: 0px 0px 8px #dcdcdc;
    background: #ffffff;
    display: flex;
    margin: -60px 22px;
    border-radius: 10px;
  }
  .me-gnan1{
    flex: 1;
    text-align: center;
    padding: 15px 0px;
  }
  .me-gnan1 img{
    width: 45px;
    height: 45px;
  }
  .me-gnan1 p{
    color: #666666;
  }
  .me-tuo{
    width: 90%;
    height: 35px;
    background: #a65f5c;
    margin: 0 22px;
    margin-top: 55px;
    border-radius: 0px 0px 10px 10px;
    display: flex;
  }
  .me-tuo1 img{
    width: 20px;
    margin-right: 5px;
  }
  .me-tuo1 span{
    position: relative;
    top: -3px;
    color: #ffffff;
  }
  .me-tuo1{
    flex: 1;
    margin: 5px 15px;
  }
  .me-tuo2 span{
    color: #ffffff;
  }
  .me-tuo2{
    margin: 6px 10px;
  }
  .me-lpdh{
    display: flex;
  }
  .me-lpdh1{
    flex: 1;
  }
  .me-lpdh1 img{
    width: 100%;
  }
  .wwt1{
    border-bottom: 1px solid #dcdcdc;
    border-top: 1px solid #dcdcdc;
  }
  .me-lianj{
    margin-top: 20px;
    margin-bottom: 50px;
  }
  .wwt2{
    border-bottom: 1px solid #dcdcdc;
  }
  .van-cell__value{
    color: #ffd876;
    font-weight: bold;
}
</style>