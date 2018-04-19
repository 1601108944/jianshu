<template>
  <div style="height:100%">
      <my-header></my-header>
      <P>我的主体内容部分</P>
  </div>
</template>
  
<script>
import myHeader from '../components/myHeader'
export default {
    head:{
       title:'简书-创作你的创作',
       meta:[
           {charset:'utf-8'},
           {name:'keywords',content:'简书首页'},
           {name:'description',content:'简书首页'},
           {name:'author',content:'张祝荣'},
       ]
    },
    components:{
        myHeader,
    },
  data() {
      return{
          naem:'首页'
      }
  }
};
</script>

<style scoped>

</style>
