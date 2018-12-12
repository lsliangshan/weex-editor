<template>
  <div class="headers">
    <a class="left"
       href="/">
      <img class="logo_img"
           src="/static/images/logo.png"
           alt="logo">
    </a>
    <div class="right">
      <div class="oper_box"></div>
      <div class="login_box">
        <a href="">登录/注册</a>
      </div>
    </div>
  </div>
</template>
<style scoped>
.headers {
  width: 1000px;
  height: 100%;
  margin: 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
.left {
  width: 240px;
  height: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  cursor: pointer;
}
.logo_img {
  height: 42px;
}
.right {
  flex: 1;
  height: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-end;
}
.login_box {
  width: 100px;
  height: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-end;
}
.oper_box {
  flex: 1;
  height: 100%;
}
</style>
<script>
export default {
  name: 'headers',
  data () {
    return {}
  }
}
</script>
