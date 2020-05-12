<template>
  <div class="login-container">
    <div class="login-box">
      <div class="avatar-box">
        <img src="../assets/logo.png" alt="logo" />
      </div>
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
}
</style>
