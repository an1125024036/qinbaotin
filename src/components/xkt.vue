<template>
  <div id="datamie">
      <div class="bt">
        <p>亲宝小课堂<img src="../assets/image/未标题-9.png"></p>
      </div>
      <div class="xbt">
        <span>积蛙步至千里，答题赢亲币</span><img src="../assets/image/dt.png">
      </div>
      <div class="bf">
          <ul>
              <li><van-icon name="play-circle-o" color="#c7c7c7" size="25" style="position: relative;top: 7px;padding-right: 15px;"/>育儿|要控制宝宝喝奶量和次数吗<span style="padding-left: 20px;color:#999999;">01:02</span></li>
              <li><van-icon name="play-circle-o" color="#c7c7c7" size="25" style="position: relative;top: 7px;padding-right: 15px;"/>育儿|要控制宝宝喝奶量和次数吗<span style="padding-left: 20px;color:#999999;">01:02</span></li>
              <li><van-icon name="play-circle-o" color="#c7c7c7" size="25" style="position: relative;top: 7px;padding-right: 15px;"/>育儿|要控制宝宝喝奶量和次数吗<span style="padding-left: 20px;color:#999999;">01:02</span></li>
              <li><span style="color:#999999">查看更多</span></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    #datamie{
        margin: 40px 20px 20px 20px;
    }
    .bt img{
        width: 20px;
        height: 20px;
        margin-left: 5px;
    }
    .bt p{
        font-size: 20px;
        color: #444444;
        font-weight: bold;
    }
    .xbt span{
        color: #999999;
        font-size: 13px;
        flex: 1;
    }
    .xbt img{
        width: 110px;
        height: 30px;
    }
    .xbt{
        display: flex;
        align-items: center;
        margin: 5px 0px 5px 0px;
    }
    .bf{
        width: 100%;
        height: 190px;
        box-shadow:0px 0px 8px #dcdcdc;
        border-radius: 15px;
        margin-top: 15px;
    }
    .bf ul li{
        padding: 10px;
        color: #333333;
        font-size: 15px;
        text-align: center;
    }
</style>