<template>
  <div class="loginconte">
      <el-card class="logincard">
          <img src="../../assets/images/logo_index.png" >

      </el-card>
  </div>
</template>
<script>
export default {
}
</script>
<style lang="less">
.loginconte{
    width: 100%;
    height: 100%;
    position: absolute;
    top:0;
    left:0;
    background: url(../../assets/images/login_bg.jpg) no-repeat center/cover
}
.logincard{
    width: 400px;
    height: 300px;
    position:absolute;
    left:50%;
    top:50%;
    transform: translate(-50%,-50%);
    img{
        display: block;
        width: 200px;
        margin: 10px,auto;
     }
}
</style>
