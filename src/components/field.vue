<template>
    <div class="mit">
        <van-search style="flex: 5;text-align: center;"
            v-model="value"
            shape="round"
            background="#ffffff"
            placeholder="春天"
            />
        <div class="ww2"><img src="../assets/image/未标题-1.png"></div>
        <div class="ww3"><img src="../assets/image/未标题-2.png"></div>
    </div>
</template>

<script>
export default {
data() {
    return {
        value:''
    }
},
}
</script>

<style>
    .mit{
        width: 100%;
        height: 50px;
        display: flex;
        position: fixed;
        background: #ffffff;
        z-index: 99;
    }
    .mit img{
        width: 30px;
    }
    .ww2{
        flex: 1;
    }
    .ww2 img{
        margin-top: 16%;
    }
    .ww3{
        flex: 1;
    }
    .ww3 img{
        margin-top: 16%;
    }
</style>