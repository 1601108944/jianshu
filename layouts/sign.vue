<template>
  <div>
    <nuxt/>
  
  </div>
</template>

<script>
// // 首先引入bootstrap.css文件
// import'bootstrap/dist/css/bootstrap.css'
// import Vue from 'vue'
// import BootstrapVue from 'bootstrap-vue'
// import'bootstrap-vue/dist/bootstrap-vue.css'

export default {
  components: {

  }
}
</script>
<style>
body{
  background-color: #F1F1F1;
}
.sign{
  width: 100%;
  font-size: 14px;
  text-align: center;
}
.sign img{
  width: 100%;
}
.sign .logo{
  position: absolute;
  left: 50px;
  top: 50px;
}
.sign .main{
  width: 400px;
  margin: 60px auto 0;
  padding: 50px 50px 30px;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 0 8px rgba(0, 0, 0, .1);
  display: inline-block;
}



.sign .main .title{
  margin: 0 auto 30px;
  color: #939393;
  font-size: 18px;
}
.sign .main h4 a,.sign .main h4 b{
  font-weight: 400;
  color: #969696;
  padding: 10px;
}
.sign .main h4 a.active{
  font-weight: 700;
  color: #ea6f5a;
  border-bottom: 2px solid #ea6f5a;
}
.sign .main h4 a:hover{
  border-bottom: 2px solid #ea6f5a;
}


.sign .main form {
  color: #969696;
  margin: 0 0 30px;
}
.sign .main form .input-prepend{
  position: relative;
  width: 100%;
}
.sign .main form .input-prepend input{
  width: 100%;
  padding: 4px 12px 4px 30px;
  height: 50px;
  border: 1px solid #c8c8c8;
  border-radius: 2px;
  background-color: rgb(248, 248, 248)
}
.sign .main form .input-prepend:nth-of-type(1) input{
  border-bottom: 0;
  border-radius: 2px 2px 0 0 ;
}
.sign .main form .input-prepend:nth-of-type(2) input{
  border-radius: 0 0 2px 2px;
}
.sign .main form .input-prepend i {
  position: absolute;
  left: 10px;
  top: 15px;
  font-size: 20px;
  color: #969696;
}

.sign .main form .remember{
  float: left;
  margin: 20px 0 ;
}
.sign .main form .help {
  float: right;
  margin: 20px 0 ;
  color: #969696;
}
.sign .main form .help:hover{
  color: #333;
}
.sign .main form button{
  width: 100%;
  margin: 20px 0 0 ;
  padding: 9px 18px ;
  text-align: center;
  color: #fff;
  background: #3194d0;
  border-radius: 25px;
  border: none;
  font-size: 18px;
  clear: both;
  outline: none;
}

.sign .main form button:hover{
  background: #187cb7;
  cursor: pointer;
}
</style>

