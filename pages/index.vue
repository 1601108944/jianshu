<template>
  <div style="...">
      <my-header></my-header>
      <div class="container index">
          <div class="row">
             <div class="col-xs-16  main">
                <!-- 热门专题 -->
                <div class="recommend-collection">
                    <nuxt-link class="collection" to="/collection/123">
                    <img src="../assets/img/c-1.jpg" alt="">
                    <span>故事</span>
                    </nuxt-link>

                    <nuxt-link class="collection" to="/collection/123">
                    <img src="../assets/img/c-3.jpg" alt="">
                    <span>摄影</span>
                    </nuxt-link>

                    <nuxt-link class="collection" to="/collection/123">
                    <img src="../assets/img/c-2.jpg" alt="">
                    <span>人文社科</span>
                    </nuxt-link>

                    <nuxt-link class="collection" to="/collection/123">
                    <img src="../assets/img/c-3.jpg" alt="">
                    <span>历史</span>
                    </nuxt-link>

                    <nuxt-link class="collection" to="/collection/123">
                    <img src="../assets/img/c-2.jpg" alt="">
                    <span>读书</span>
                    </nuxt-link>

                    <nuxt-link  to="/collection/123" class="more-collection">
                        更多热门专题
                        <i class="fa fa-angle-right"></i>
                    </nuxt-link>
                
                </div>
                <div class="spilt-line"></div>
             </div>
             <div class="col-xs-offset-1 col-xs-7 aside" >
                 侧边栏
             </div>
          </div>
      </div>
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
