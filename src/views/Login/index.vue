<template>
    <div class="login-container">
        <el-card class="login-box">
            <img src="../../assets/images/logo_index.png" alt="">
        </el-card>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="less">
    .login-container{
        width: 100%;
        height: 100%;
        position: absolute;
        left: 0;
        top: 0;
        background: url(../../assets/images/login_bg.jpg) no-repeat center / cover;
        .login-box{
            position: absolute;
            width: 400px;
            height: 300px;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            img{
                display: block;
                width: 200px;
                margin: 10px auto;
            }
        }
    }
</style>
