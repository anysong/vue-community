<template>
    <div class="header">
       <div class="header-wrap">
           <img class="logo" src="" alt="">
           <ul class="nav">
               <!-- <li>
                   <router-link to="/">Home</router-link>
               </li>
                <li>
                   <router-link to="/detail">detail</router-link>
               </li> -->
               <li><a href="http://yfb2.jdata.jd.com/index.html">首页</a></li>
               <li><a href="http://yfb2.jdata.jd.com/html/list.html">竞赛</a></li>
               <li><a href="http://yfb2.jdata.jd.com/html/knowledge.html">知识库</a></li>
               <li><a href="">排名与奖励</a></li>
               <li><a href="/">社区</a></li>
               <li><a href="">关于我们</a></li>
           </ul>
       </div>
    </div>
</template>
<style lang="less" scoped>
    .header {
        width: 100%;
        height: 50px;
        background-color: #000;
        .header-wrap {
            width: 1400px;
            height: 100%;
            margin: 0 auto;
            .logo {
                width: 200px;
                height: 100%;
                display: block;
                float: left;
            }
            .nav {
                margin: 0;
                padding: 0;
                list-style: none;
                float: left;
                &::after {
                    content: '';
                    height: 0;
                    visibility: hidden;
                    clear: both;
                    display: block;
                }
                li {
                    float: left;
                    padding: 0 20px;
                    line-height: 50px;
                    a {
                        color: #fff;
                        text-decoration: none;
                        font-size: 14px;
                        font-weight: bold;
                    }
                }
            }
        }
    }
</style>

