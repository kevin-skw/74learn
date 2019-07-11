<template>
  <div class="loginconte">
      <el-card class="logincard">
          <img src="../../assets/images/logo_index.png" >
<el-form :model="ruleForm" ref="ruleForm" label-width="100px" class="demo-ruleForm">
  <el-form-item label="密码" >
    <el-input type="" v-model="ruleForm.pass" autocomplete="off"></el-input>
  </el-form-item>
  <el-form-item label="确认密码" prop="checkPass">
    <el-input type="password" v-model="ruleForm.checkPass" autocomplete="off"></el-input>
  </el-form-item>
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
        margin: 10px auto;
     }
}
</style>
