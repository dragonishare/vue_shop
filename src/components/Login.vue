<template>
  <div class="login-container">
    <div class="login-box">
      <!-- 头像区域 -->
      <div class="avatar-box">
        <img src="../assets/logo.png" alt="logo" />
      </div>
      <!-- 登录表单区域 -->
      <el-form label-width="0px" class="login-form">
        <!-- 用户名 -->
        <el-form-item>
          <el-input prefix-icon="iconfont icon-user"></el-input>
        </el-form-item>
        <!-- 密码 -->
        <el-form-item>
          <el-input prefix-icon="iconfont icon-3702mima"></el-input>
        </el-form-item>
        <!-- 按钮区域 -->
        <el-form-item class="btns">
          <el-button type="primary">登录</el-button>
          <el-button type="info">重置</el-button>
        </el-form-item>
      </el-form>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style lang="less" scoped>
.login-container {
  height: 100%;
  color: #fff;
  background: #2b4b6b;
}
.login-box {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 450px;
  height: 300px;
  background: #fff;
  border-radius: 5px;
  .avatar-box {
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 130px;
    height: 130px;
    padding: 10px;
    border: 1px solid #eee;
    background: #fff;
    border-radius: 50%;
    box-shadow: 0 0 10px #ddd;
    img {
      display: block;
      width: 100%;
      height: 100%;
      background: #eee;
      border-radius: 50%;
    }
  }
  .login-form {
    position: absolute;
    bottom: 0;
    width: 100%;
    padding: 0 20px;
    box-sizing: border-box;
    .btns {
      display: flex;
      justify-content: flex-end;
    }
  }
}
</style>
