<template>
    <div>
        <div class="user-head-box">
            <!-- <img class="user-head" src="static/images/user.jpeg" alt="guangyan"> -->
            <img class="user-head" src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=489846772,2186389734&fm=26&gp=0.jpg" alt="guangyan">
            <h3 class="title">Guangyan的简历</h3>
        </div>
        <div class="basic-info-box">
            <h2 class="basic-info-title red-background">基本信息</h2>
            <ul class="basic-info-ul">
                <li>
                    <span>姓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;名：</span> 罗贤良
                </li>
                <li>
                    <span>性&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;别：</span> 男
                </li>
                <li>
                    <span>毕业院校：</span> 江西农业大学南昌商学院
                </li>
                <li>
                    <span>毕业时间：</span> 2015年7月
                </li>
            </ul>
        </div>
        <div class="contact-box">
            <h2 class="contact-title green-background">联系方式</h2>
            <ul class="contact-ul">
                <li>
                    <span><i class="iconfont icon-phone"></i>电话：</span> 18070514832
                </li>
                <li>
                    <span><i class="iconfont icon-email"></i>邮箱：</span> 1527628594@qq.com
                </li>
                <li>
                    <span><i class="iconfont icon-weixin"></i>微信：</span> lxl18070514832
                </li>
                <li>
                    <span><i class="iconfont icon-qq"></i>QQ：</span> 1527628594
                </li>
            </ul>
        </div>
        <div class="job-box" style="margin-bottom:20px;">
            <h2 class="job-title yellow-background">求职意向</h2>
            <ul class="job-ul">
                <li><span>python研发工程师/机器学习</span></li>
            </ul>
        </div>
        <div class="introduce-box">
            <p class="introduce-content">我是一个对人工智能和机器学习由衷热爱，充满向往的服务端工程师。目前正在寻找人工智能和机器学习相关工作机会，希望在人工智能技术开发领域能够很好的拓展各方面技术能力。</p>
        </div>
    </div>
</template>
<style scoped>
.user-head-box{
    width: 100%;
    padding: 20px;
    box-sizing: border-box;
    clear: both;
}
.user-head-box .user-head{
    display: block;
    margin: 0 auto;
    width: 132px;
    height: 132px;
    border: 4px solid white;
    border-radius: 50%;
}
.user-head-box .title{
    text-align: center;
}
.basic-info-box,
.contact-box,
.job-box{
    width: 100%;
    height: auto;
    margin-bottom: 36px;
}
.introduce-box{
    width: 100%;
    height: auto;
    box-sizing: border-box;
    padding-left: 40px;
    padding-right: 10px;
}
.introduce-box .introduce-content{
    display: inline-block;
    line-height: 1.6;
    text-indent: 2em;
    font-size: 14px;
    font-weight: inherit;
}

/* .basic-info-box::before{
    position: absolute;
    left: -30px;
    content: "";
    display: block;
    width: 0;
    height: 0;
    border: 21px solid;
    border-color: #394A5A #B05051 #394A5A #394A5A;
}
.basic-info-box::after{
    position: absolute;
    content: "";
    display: block;
    bottom: -10px;
    border: 15px solid;
    border-color: ;
} */
.basic-info-box .basic-info-title,
.contact-box .contact-title,
.job-box .job-title{
    font-weight: 400;
    margin: 0 0 0 30px;
    padding-left: 21px;
    height: 42px;
    line-height: 42px;
    position: relative;
    right: -15px;
    box-sizing: border-box;
    border-top-right-radius: 4px;
    box-shadow: 0 2px 2px 0 rgb(0 0 0 / 14%), 0 3px 1px -2px rgb(0 0 0 / 20%), 0 1px 5px 0 rgb(0 0 0 / 12%);
}
.basic-info-box .basic-info-title::before,
.contact-box .contact-title::before,
.job-box .job-title::before{
    position: absolute;
    left: -16px;
    top: 0;
    content: "";
    width: 20px;
    height: 42px;
    /* border-right: 15px solid #B05051;
    border-left: 0 solid transparent;
    border-bottom: 15px solid transparent; */
    /* border: 21px solid;
    border-color:  #394A5A #B05051 #394A5A #394A5A; */
    clip-path: polygon(80% 0%, 100% 0%, 100% 100%, 80% 100%, 0% 50%);
}
.basic-info-box .basic-info-title::after,
.contact-box .contact-title::after,
.job-box .job-title::after{
    position: absolute;
    content: "";
    width: 0;
    height: 0;
    right: 0;
    top: 100%;
    border-left-width: 15px;
    border-left-style: solid;
    border-bottom: 15px solid transparent;
    border-right: 0 solid transparent;
}
/* 红色背景 */
.red-background{
    background-color: #B05051;
    border-color: #6B3645;
}
.red-background::before{
    background-color: #B05051;
}
.red-background::after{
    border-left-color: #6B3645;
}
/* 绿色背景 */
.green-background{
    background-color: #BDC293;
    border-color: #5A6238;
}
.green-background::before{
    background-color: #BDC293;
}
.green-background::after{
    border-left-color: #5A6238;
}
/* 黄色背景 */
.yellow-background{
    background-color: #DAB652;
    border-color: #887334;
}
.yellow-background::before{
    background-color: #DAB652;
}
.yellow-background::after{
    border-left-color: #887334;
}

.basic-info-box .basic-info-ul,
.contact-box .contact-ul,
.job-box .job-ul{
    list-style: none;
    font-size: 14px;
    margin-left: 30px;
}
.basic-info-box .basic-info-ul li,
.contact-box .contact-ul li,
.job-box .job-ul li{
    margin: 5px auto;
}

.contact-box .contact-ul li span,
.job-box .job-ul li span{
    font-weight: bold;
}

.contact-box .contact-ul i{
    padding: 5px;
}
</style>
