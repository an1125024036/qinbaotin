<template>
    <div class="dh">
        <div class="dhlb">
            <div class="pic1">
                <img src="../assets/image/未标题-4.png">
                <p>必听</p>
            </div>
            <div class="pic1">
                <img src="../assets/image/未标题-5.png">
                <p>场景</p>
            </div>
            <div class="pic1">
                <img src="../assets/image/未标题-6.png">
                <p>主播</p>
            </div>
            <div class="pic1">
                <img src="../assets/image/未标题-7.png">
                <p>榜单</p>
            </div>
            <div class="pic1">
                <img src="../assets/image/未标题-8.png">
                <p>分类</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    p{
        margin: 0px;
        padding: 0px;
    }
    .dhlb{
      display: flex;
    }
    .pic1{
        flex: 1;
        text-align: center;
    }
    .pic1 img{
        width: 50px;
        height: 55px;
        justify-content: center;
        justify-items: center;
    }
    .pic1 p{
        font-size: 13px;
        color: #666666;
        text-align: center;
        margin-top: 10px;
    }
    .dhlb{
        margin: 10px;
        margin-top: 20px;
    }
</style>