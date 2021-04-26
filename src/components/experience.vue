<template>
    <div class="right-box">
        <div class="main-box">
        <div class="technologe-box">
            <h3><i class="iconfont icon-rocket-full rocket"></i>技术栈</h3>
            <!-- <h4 class="technolog-title">服务端</h4> -->
            <ul class="item-list">
                <li>
                    <h5>服务端</h5>
                    <p>熟悉<span class="red">python</span>编程语言，flask框架，<span class="red">postgresql</span>关系型数据库，以及<span class="red">redis</span>缓存，能够独立搭建和开发python相关项目服务，以及定时计划任务；</p>
                    <p>熟悉自动化爬虫流程，能够应用requests库搭建自动化爬虫系统工具；了解selenium(web自动化爬虫工具)、scrapy爬虫框架；</p>
                    <p>熟悉<span class="red">golang</span>编程语言，gin框架，能够应用golang及相关技术搭建接口服务；</p>
                    <p>熟悉<span class="red">Linux</span>相关基础命令，了解ngnix服务器，能够基于linux系统平台，安装和配置nginx相关文件；</p>
                    <p>熟悉supervisor进程管理工具，能够基于linux系统平台，安装和配置supervisor项目启动文件；</p>
                    <p>熟悉<span class="red">git</span>版本管理工具，以及相关命令的应用；</p>
                    <p>了解cdn加速，以及负载均衡；</p>
                </li>
                <li>
                    <h5>前端</h5>
                    <p>熟悉html、css、js、jquery、bootstrap,了解css3,能够根据设计图制作前端静态页面；</p>
                    <p>熟悉<span class="red">vue</span>，了解webpack构建工具，以及eslint代码检测工具，自主学习less、scss，能够使用vue搭建前端项目服务；</p>
                    <p>了解<span class="red">element-ui</span>组件库，了解<span class="red">vant</span>组件库，能够将element-ui、vant组件库应用到前端项目中，制作相关组件及功能；</p>
                    <p>了解微信小程序、以及微信公众号制作；</p>
                </li>
            </ul>
        </div>
        <div class="experience-box">
            <h3><i class="iconfont icon-rocket-full rocket"></i>项目与工作经验</h3>
            <h4 class="company-title">中至数据集团股份有限公司&nbsp;&nbsp;(2017.06 —— 至今)</h4>
            <ul class="item-list">
                <li>
                    <h5>Python研发工程师</h5>
                    <p>主要负责广告管理系统和h5前端页面制作，自动化数据爬虫工具研发，红包后台管理系统制作，h5支付结果页面制作，以及crontab定时处理数据脚本制作。</p>
                    <p>应用python和postgresql关系型数据库，以及redis缓存开发相关项目；基于linux系统平台，使用crontab制作定时任务脚本服务，以及使用schedule库搭建定时执行任务服务；持续优化相关产品项目服务质量、用户体验。</p>
                    <p>基于Linux服务平台，应用nginx+supervisor部署项目服务。</p>
                    <p>应用h5 + css3 制作动态动画效果，使用ajax异步请求完成相关页面与服务端数据交互。</p>
                </li>
                <li>
                    <h5>golang研发工程师</h5>
                    <p>大型公司内部管理系统开发，主要负责相关内部后台和客户端接口开发，以及定时脚本服务搭建和功能制作。</p>
                    <p>应用golang和postgresql关系型数据库，以及redis缓存开发相关接口项目服务，搭建定时执行任务脚本服务。</p>
                    <p>协助前端应用vue + webpack开发后台相关页面，以及功能。</p>
                </li>
            </ul>
            <h4 class="company-title">江西华邦传媒有限公司&nbsp;&nbsp;(2015.12 —— 2016.10)</h4>
            <ul class="item-list">
                <li>
                    <h5>软件开发工程师</h5>
                    <p>主要负责后台管理系统开发，以及企业站、教育网站建设。</p>
                    <p>应用php + mysql作为服务端开发项目，使用jquery+ajax完成部分模块功能数据交互，协助前端调整前端页面样式布局。</p>
                </li>
            </ul>
        </div>
    </div>
    </div>
</template>

<style scoped>
@import url('https://at.alicdn.com/t/font_2485272_5dk48a109n.css');
.main-box{
    width: 100%;
    height: auto;
    background-color: white;
    padding: 10px 0px;
    box-sizing: border-box;
}
.main-box .experience-box,
.main-box .technologe-box{
    width: 100%;
    height: auto;
}
.main-box .experience-box h3,
.main-box .technologe-box h3{
    color:#394A5A;
    font-size: 24px;
    font-weight: inherit;
    border-bottom: 1px solid #394A5A;
}
.main-box .experience-box h3 .rocket,
.main-box .technologe-box h3 .rocket{
    font-size: 22px;
    margin: auto 5px;
}
.main-box .experience-box .company-title,
.main-box .technologe-box .technolog-title{
    margin: auto 10px;
    font-size: 18px;
    color: #01579B;
}
.main-box .experience-box .item-list,
.main-box .technologe-box .item-list{
    height: auto;
    list-style: none;
    line-height: 1.6;
    margin-left: 15px;
    padding-left: 15px;
    border-left: 2px solid #394A5A;
}
.main-box .experience-box .item-list h5,
.main-box .experience-box .item-list p,
.main-box .technologe-box .item-list h5,
.main-box .technologe-box .item-list p{
    margin: 0;
    padding: 0;
}
.main-box .experience-box .item-list li,
.main-box .technologe-box .item-list li{
    position: relative;
    margin-bottom: 15px;
}
.main-box .experience-box .item-list li::before,
.main-box .technologe-box .item-list li::before{
    position: absolute;
    left: -22.5px;
    top: 5px;
    content: "";
    width: 15px;
    height: 15px;
    background-color: #394A5A;
    border-radius: 50%;
}
.main-box .experience-box .item-list li:nth-child(1)::after,
.main-box .technologe-box .item-list li:nth-child(1)::after{
    position: absolute;
    left: -22.5px;
    top: -10px;
    content: "";
    width: 15px;
    height: 15px;
    background-color: white;
    border-radius: 50%;
}
.main-box .experience-box .item-list h5,
.main-box .technologe-box .item-list h5{
    font-size: 18px;
}
.main-box .experience-box .item-list p,
.main-box .technologe-box .item-list p{
    color: #666;
}
span.red{
    color: red;
}
</style>>
