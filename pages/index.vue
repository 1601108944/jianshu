<template>
    <div id="index" style="height:100%">
        <my-header></my-header>
        <div class="container index">
            <div class="row">
                <div class="col-xs-16 main">
                    <!--热门专题-->
                    <div class="recommend-collection">
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="../assets/img/c-1.jpg">
                            <span name="name">故事</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="../assets/img/c-2.jpg">
                            <span name="name">摄影</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="../assets/img/c-3.jpg">
                            <span name="name">人文社科</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="../assets/img/c-1.jpg">
                            <span name="name">历史</span>
                        </nuxt-link>
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="../assets/img/c-2.jpg">
                            <span name="name">读书</span>
                        </nuxt-link>
                        <nuxt-link class="more-collection" to="/">
                            更多热门专题
                            <i class="fa fa-angle-right"></i>
                        </nuxt-link>   
                    </div>
                    <div class="split-line"></div>
                    <!--文章列表-->
                    <div class="list-container">
                        <ul class="note-list">
                            <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="../assets/img/node.jpg" style="width:150px;height:120px">
                                </nuxt-link>
                                <div class="content">
                                    <div class="authod">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="../assets/img/1.png">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">
                                                测试用户
                                            </nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <div class="title">你为什么写作？我写作是为了挣钱，你呢？</div>
                                    <div class="abstruct">壹 热门文章的作者都到哪里去了？故事专题最热的文章是《对啊，就是嫌你穷才分手的啊》，作者七毛就是我，最新的作品是2016.11；还有宋小君、入江之鲸等等，他们都在简书里消失了..</div>
                                    
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                                <i class="fa fa-eye"></i>
                                                1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                                <i class="fa fa-comment"></i>
                                                100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-hear"></i>
                                            20
                                        </span>
                                    </div>
                                </div>
                            </li>
                            <li>
                                <div class="content">
                                    <div class="authod">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="../assets/img/1.png">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="/u/123" class="nickname">
                                                测试用户
                                            </nuxt-link>
                                            <span class="time">
                                                04.12 10:18
                                            </span>
                                        </div>
                                    </div>
                                    <div class="title">你为什么写作？我写作是为了挣钱，你呢？</div>
                                    <div class="abstruct">壹 热门文章的作者都到哪里去了？故事专题最热的文章是《对啊，就是嫌你穷才分手的啊》，作者七毛就是我，最新的作品是2016.11；还有宋小君、入江之鲸等等，他们都在简书里消失了..</div>
                                    <div class="meta">
                                        <nuxt-link to="/p/123">
                                            <span>
                                                <i class="fa fa-eye"></i>
                                                1500
                                            </span>
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <span>
                                                <i class="fa fa-comment"></i>
                                                100
                                            </span>
                                        </nuxt-link>
                                            <span>
                                                <i class="fa fa-hear"></i>
                                                20
                                            </span>
                                    </div>
                                </div>
                            </li>
                        </ul>
                        
                    </div>

                    <a href="#" class="load-more">阅读更多</a>
                </div>
                <div class="col-xs-offset-1 col-xs-7 aside">
                <div class="row">
                    <div class="board">
                        <nuxt-link to="/">
                          <img src="../assets/img/ad1.png" alt="">
                        </nuxt-link>
                            <nuxt-link to="/">
                          <img src="../assets/img/ad2.png" alt="">
                        </nuxt-link>
                        <nuxt-link to="/">
                          <img src="../assets/img/ad3.png" alt="">
                        </nuxt-link>
                        <nuxt-link to="/">
                          <img src="../assets/img/ad4.png" alt="">
                        </nuxt-link>
                    </div>

                        <!--推荐作者-->
                        <div class="recommended-author">
                            <div class="title">
                                <span>推荐作者</span>
                                <nuxt-link class="page-change" to="/">
                                    <i class="fa fa-refresh "></i>
                                    换一批
                                </nuxt-link>
                            </div>
                            <ul class="recommended-list">
                                <li>
                                    <nuxt-link class="avatar" to="/u/123">
                                        <img src="../assets/img/default-avatar.jpg">
                                    </nuxt-link>
                                    <a href="#" class="follow">
                                        <i class="fa fa-plus"></i>
                                        关注
                                    </a>
                                    <nuxt-link to="/u/123" class="name">
                                        简书用户
                                    </nuxt-link>
                                    <p>
                                        写了1958k字·1.9k喜欢
                                    </p>
                                </li>
                                <li>
                                    <nuxt-link class="avatar" to="/u/123">
                                        <img src="../assets/img/default-avatar.jpg">
                                    </nuxt-link>
                                    <a href="#" class="follow">
                                        <i class="fa fa-plus"></i>
                                        关注
                                    </a>
                                    <nuxt-link to="/u/123" class="name">
                                        简书用户
                                    </nuxt-link>
                                    <p>
                                        写了1958k字·1.9k喜欢
                                    </p>
                                </li>
                                <li>
                                    <nuxt-link class="avatar" to="/u/123">
                                        <img src="../assets/img/default-avatar.jpg">
                                    </nuxt-link>
                                    <a href="#" class="follow">
                                        <i class="fa fa-plus"></i>
                                        关注
                                    </a>
                                    <nuxt-link to="/u/123" class="name">
                                        简书用户
                                    </nuxt-link>
                                    <p>
                                        写了1958k字·1.9k喜欢
                                    </p>
                                </li>
                                <li>
                                    <nuxt-link class="avatar" to="/u/123">
                                        <img src="../assets/img/default-avatar.jpg">
                                    </nuxt-link>
                                    <a href="#" class="follow">
                                        <i class="fa fa-plus"></i>
                                        关注
                                    </a>
                                    <nuxt-link to="/u/123" class="name">
                                        简书用户
                                    </nuxt-link>
                                    <p>
                                        写了1958k字·1.9k喜欢
                                    </p>
                                </li>
                                <li>
                                    <nuxt-link class="avatar" to="/u/123">
                                        <img src="../assets/img/default-avatar.jpg">
                                    </nuxt-link>
                                    <a href="#" class="follow">
                                        <i class="fa fa-plus"></i>
                                        关注
                                    </a>
                                    <nuxt-link to="/u/123" class="name">
                                        简书用户
                                    </nuxt-link>
                                    <p>
                                        写了1958k字·1.9k喜欢
                                    </p>
                                </li>
                            </ul>
                            <nuxt-link to="/" class="find-more">
                                查看更多
                                <i class="fa fa-angle-right"></i>
                            </nuxt-link>
                        </div>
                </div>
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
