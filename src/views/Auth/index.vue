<template>
  
  <div class="auth">
    <div class="bg"></div>
    <div class="title-info">
      <img src="https://img2.baidu.com/it/u=1484318800,4151532720&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=500" alt="">
      <h2 class="title">图书管理系统</h2>
    </div>

    <div class="form">
      <a-tabs>
        <a-tab-pane key="1" tab="登入">
          <div class="item">
            <a-input size="large" placeholder="账号">
              <template #prefix>
                <UserOutlined />
              </template>
            </a-input>
          </div>
          <div>
            <a-input size="large" placeholder="密码"> 
              <template #prefix>
                <LockOutlined />
              </template>
            </a-input>
          </div> 
          <div class="item">
            <a href="">忘记密码</a>
          </div>

          <div class="item">
            <a-button size="large" type="primary">
                登入
            </a-button>
          </div>

        </a-tab-pane>
        <a-tab-pane key=2 tab="注册">
          <div class="item">
            <a-input size="large" placeholder="账号">
              <template #prefix>
                <UserOutlined />
              </template>
            </a-input>
          </div>


          <div>
            <a-input size="large" placeholder="密码"> 
              <template #prefix>
                <LockOutlined />
              </template>
            </a-input>
          </div> 

          <div>
            <a-input size="large" placeholder="邀请码">
              <template #prefix>
                <MailOutlined />
              </template>
            </a-input>
          </div> 

          <div class="item">
            <a-button size="large" type="primary">
                注册
            </a-button>
          </div>
        </a-tab-pane>
      </a-tabs>
    </div>


  </div>

</template>
<script src="./index.js">

</script>

<style lang="scss" scpoed>
    @import './index.scss';
</style>