<template>
  <div class="login">
    <el-card class="login-card">
      <div class="logo">
        <img src="../../assets/img/logo_index.png" alt="" />
      </div>
      <el-form ref="form" >
        <el-form-item>
          <el-input placeholder="请输入手机号" style="margin-top:20px"></el-input>
        </el-form-item>
        <el-form-item>
          <el-input placeholder="请输入验证码" style="width:250px"></el-input>
          <el-button type="primary" style="float:right">获取验证码</el-button>
        </el-form-item>
        <el-form-item>
        <el-checkbox >是否同意</el-checkbox>
        </el-form-item>
        <el-form-item style="text-align: center">
          <el-button type="primary" style="width:100%">登录</el-button>
        </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>

<script>
export default {}
</script>

<style lang = 'less' scoped>
.login {
  background-image: url("../../assets/img/login_bg.jpg");
  height: 100vh;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  .login-card {
    width: 440px;
    height: 350px;
    .logo {
      text-align: center;
      img {
        height: 45px;
      }
    }
  }
}
</style>
