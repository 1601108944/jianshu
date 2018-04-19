<template>
  <div>
      <nav class="navbar navbar-fixed-top">
      <div class="width-limit">
          <!-- logo -->
          <nuxt-link class="logo" to="/">
        <img src="../assets/img/nav-logo.png" alt="">
          </nuxt-link>
        <!-- 右上角，写文章 -->
        <nuxt-link to="/write" class="write-btn">
        <i class="fa fa-edit">写文章</i>
        </nuxt-link>

        <!-- 登陆用户信息 -->
        <div class="user">
              <div class="drop-down">
               <nuxt-link to="/u123" class="avatar">
              <img src="../assets/img/default-avatar.jpg" alt="">
               </nuxt-link>
              </div>
              <ul class="drop-menu">
                  <li>
                     <nuxt-link to="/user/123">
                      <i class="fa fa-home"></i>
                      我的主页
                     </nuxt-link>
                  </li>
                  <li>
                      <nuxt-link to="/user/123/like">
                        <i class="fa fa-heart"></i>
                        喜欢的文章
                      </nuxt-link>
                  </li>
                  <li>
                      <nuxt-link to="/bookmarks">
                          <i class="fa fa-bookmark"></i>
                          收藏的文章
                      </nuxt-link>
                  </li>
                  <li>
                      <nuxt-link to="/settings/basic">
                          <i class="fa fa-cog"></i>
                          设置
                      </nuxt-link>
                  </li>
                  <li>
                      <nuxt-link to="/logout">
                          <i class="fa fa-sign-out"></i>
                          退出
                      </nuxt-link>
                  </li>
              </ul>
        </div>
        <!-- 右上角，登陆和注册 -->

      </div>
      </nav>
  </div>
</template>

<script>
export default {
  name: "myHeader"
};
</script>


<style scoped>
nav {
  height: 56px;
  width: 100%;
  border-bottom: 1px solid #fff;
}
.navbar:before {
  content: "";
  display: table;
}
.navbar {
  margin-bottom: 20px;
  border-width: 0 0 1px;
  border-color: #f0f0f0;
  background: #fff;
}
.navbar-fixed-top {
  position: fixed;
  left: 0;
  top: 0;
  z-index: 9999;
}
.width-limit {
  max-width: 1440px;
  min-width: 768px;
  margin: 0 auto;
}

nav .logo {
  float: left;
  height: 56px;
}
nav .logo img {
  height: 100%;
}
nav .write-btn{
    float: right;
    width: 100px;
    height: 40px;
    line-height: 40px;
    margin: 8px 15px 0 ;
    border-radius: 20px;
    font-size: 15px;
    color: #fff;
    background: #ea6f5a;
    text-align: center;
}
nav .write-btn:hover{
    background: #ec6149;
}

nav .user{
    position: relative;
    float: right;
}

nav .user .avatar{
    position: relative;
    display: block;
    width: 40px;
    height: 40px;
    margin: 8px 28px 8px 20px;
}
nav .user .avatar:before{
    content:'';
    position: absolute;
    border-left: 5px solid transparent;
    border-right: 5px solid transparent;
    border-top: 5px solid #999;
    top: 18px;
    right: -14px;
}
nav .user .avatar img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border:1px solid #eee;
}
</style>

