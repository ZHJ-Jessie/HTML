# HTMLSkip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 @ZHJ-Jessie Sign out
0
0 0 ZHJ-Jessie/HTML
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Insights  Settings
HTML/<作业>网易严选.html
@ZHJ-Jessie ZHJ-Jessie Rename 网易严选.html to <作业>网易严选.html
6a9e6f7  a day ago
411 lines (392 sloc)  11.7 KB
    
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>网易严选 - 以严谨的态度，为中国消费者甄选天下优品</title>
<style type="text/css">
    body{
        margin:0px;
        min-width: 1090px;
        background-color: #fff; 
        font-size:12px;
        font: 12px/1.5 "Microsoft Yahei","微软雅黑",verdana;
    }
    ul{
        list-style:none;    
    }
    .navtop{
        margin:0px;
        height: 36px;
        background-color: #333;
    }
    .nav-jz{
        width:1090px;
        margin-right:auto;
        margin-left:auto;
    }
    .nav-p{
        padding:0px;
        margin:0px;  
        float: left;
        color: #ccc;
        line-height: 36px;
        display: block;
        -webkit-margin-before: 0em;
        -webkit-margin-after: 0em;
        -webkit-margin-start: 0px;
        -webkit-margin-end: 0px;    
    }
    .nav-n{
        color:#b4a078;
        
        float: left;
        margin-left:30px;   
        
        background: url(images/laba2.gif) center left no-repeat;
        
    }
    .nav-n ul{
        margin:auto;
        padding:0px;
    }
    .nav-n li{
        line-height:36px;
        margin:auto;
        padding:0px 0px 0px 26px;
        background: url(http://yanxuan.nosdn.127.net/d132c2561f18f1149d566a60d05fd9b7.gif) center left no-repeat;
    }
    .nav-n a{
        color:#b4a078;  
    }
    .nav-right{
        float:right;
        height:36px;
    }
    .login,.register,.nav-khzx{
        color: #ccc;
        float: left;
        line-height: 35px;
        margin-right: 20px;
        text-decoration:none;
        }
    .nav-split{
        margin: 10px 10px 10px 0;
        height: 16px;
        border-left: 1px solid #5c5c5c;
        color: #ccc;
        float: left;
        line-height: 35px;  
        }
    .nav-yxtd,.nav-qycg,.nav-khzx{
        margin-right:10px;
        line-height:35px;
        float:left;
        color:#ccc;
        text-decoration:none;
        }
    .nav-khzx > span > i{
        line-height:36px;
        background-image: url(http://mimg.127.net/hxm/yanxuan-web/p/20150730/style/img/header-s63686fd389-4827c33dfe.png);
        background-repeat: no-repeat;
        vertical-align: top;
        margin-top: 14px;
        margin-left: 10px;
        display: inline-block;
        width: 9px;
        height: 5px;
        background-position: 0 -19px;
    }
    .nav-app{
        color: #ccc;
        float: left;
        line-height: 35px;  
    }
    .nav-app span i{
        float: left;
        margin-right: 6px;
        margin-top: 12px;
        background-position: 0 -4363px;
        height: 11px;
        width: 7px;
        background-image: url(http://mimg.127.net/hxm/yanxuan-web/p/20150730/style/img/icon-normal-s934d596448-601013a26f.png);
    }
    .nav-tab{
        height: 204px;
        position: relative;
        background-color: #fff;
    }
    .nav-row{
        position: relative;
        width: 1090px;
        height: 204px;
        margin-right: auto;
        margin-left: auto;
        background-color:#fff;
    }
    .nav-logo{
        position: absolute;
        top: 0;
        left: 308px;
        z-index: 0;
        width: 400px;
        height: 150px;
        display: block;
    }
    .nav-inner{
        position: relative;
        color: #333;
    }
    .nav-search{
        position: relative;
        margin-top: 65px;
        float: right;
        width: 400px;
        margin-right: -20px;
    }
    .nav-sousuo{
        float: right;
        padding-left: 20px;
        position: relative;
        margin-left: 0px;
    }
    .nav-sousuo-logo{
        cursor: pointer;
        padding-top: 9px;
        float: right;
    }
    .nav-sousuo-icon{
        background-position: 0 -5537px;
        height: 22px;
        width: 22px;
        background-image: url(http://mimg.127.net/hxm/yanxuan-web/p/20150730/style/img/icon-normal-s934d596448-601013a26f.png);
        overflow: hidden;
        display: inline-block;
        overflow: hidden;
        vertical-align: top;
        font-size: 12px;
        word-spacing: normal;
        letter-spacing: normal;
    }
    .nav-sousuo-text{
        position: absolute;
        top: 14px;
        left: 31px;
        color: #999;
        display: block;
        line-height: 1;
        cursor: text;
        touch-action: none;
    }
    .nav-sousuo-input{
        z-index: 99;
        margin: 0;
        padding: 0;
        border:none;
        border-bottom: 1px solid #D8CEBC;
        font-size: 12px;
        line-height: 23px;
        color: #333;
        width: 252px;
        margin-top: 9px;
        height: 23px;
        float: right;
    }
    .nav-gouwu{
        padding-right: 0;
        font-size: 14px;
        height: 31px;
        width: 63px;
        text-decoration: none;
        cursor: auto;
        float: right;
        padding-left: 20px;
    }
    .icon-gouwu-logo{
        float: left;
        display: inline-block;
        overflow: hidden;
        margin-top: 9px;
        margin-right: 5px; /* 5px */
        background-position: 0 -343px;
        height: 23px;
        width: 23px;
        background-image: url(http://mimg.127.net/hxm/yanxuan-web/p/20150730/style/img/icon-normal-s934d596448-601013a26f.png);
    }
    .icon-gouwu-shu{
        float: left;
        font-style: normal;
        font-weight: bold;
        display: inline-block;
        overflow: hidden;
        color: #fff;
        text-align: center;
        line-height: 20px;
        margin-left: -13px;
        background-position: 0 -282px;
        height: 19px;
        width: 19px;
        background-image: url(http://mimg.127.net/hxm/yanxuan-web/p/20150730/style/img/icon-normal-s934d596448-601013a26f.png);
        background-repeat: no-repeat;
    }
    .tab-list{
        margin: 0;
        padding: 0;
        display: block;
        float: left;
        margin-top: 56px;
        line-height: 1;
        height: 30px;
        position: relative;
        width: 100%;
        font-weight: 700;
        list-style: none;
    }
    .tab-list-home{
        margin: 0;
        padding: 0;
        display: list-item;
        margin-left: 12px;
        padding-left: 30px;
        float: left;
        padding: 6px 29px 0;
        font-size: 14px;
    }
    .tab-list-item{
        margin: 0;
        padding: 0;
        display: list-item;
        float: left;
        padding: 6px 30px 0;
        font-size: 14px;
    }
    .tab-list-a{
        position: relative;
        z-index: 2;
        display: block;
        padding-bottom: 6px;
        color: #000;
        text-decoration: none;
        font-size: 14px;
    }
    .tab-list-split{
        margin: 0;
        padding: 0;
        border-left: 1px solid #ccc;
        height: 20px;
        margin-top: 3px;
        float: left;
        display: list-item;
    }
    .tab-list-home > .tab-list-a{
        border-bottom: 3px solid #b4a078;
        color: #b4a078;  
    }
    .tab-list-a:hover{
        border-bottom: 3px solid #b4a078;
        color: #b4a078;
    }
    .g-bd-logo{
        position: relative;
        overflow: hidden;
        height: 420px;
    }
    .g-bd-tu{
        height: 420px;
        transform: translate3d(0,0,0);
        z-index: 0;
        overflow: hidden;
        margin: 0;
        padding: 0;
    }
      .tab-list-a:hover{
        border-bottom: 3px solid #b4a078;
        color: #b4a078;
    }
    .g-bd-logo{
        position: relative;
        overflow: hidden;
        height: 420px;
    }
    .g-bd-tu{
        height: 420px;
        transform: translate3d(0,0,0);
        z-index: 0;
        overflow: hidden;
        margin: 0;
        padding: 0;
    }
</style>
</head>

<body>
	<header>
        <div class="navtop">
        	<div class="nav-jz">
            	<p class="nav-p">好的生活，没那么贵</p>
                <div class="nav-n">
                	<ul>
                    	<li>
                        	<a href="https://www.baidu.com" target="_blank">端午假期部分商品暂停发货公告</a>
                        </li>
                    </ul>
                </div>
				<div class="nav-right">
                	<a class="login" href="http://www.baidu.com">登录</a>
                    <a class="register">注册</a>
                    <div class="nav-split"></div>
                    <a class="nav-yxtd">严选态度</a>
                    <div class="nav-split"></div>
                    <a class="nav-qycg">企业采购</a>
                    <div class="nav-split"></div>
                    <div class="nav-khzx">
                    	<span>
                        	客户服务
                            <i></i>
                        </span>
                    </div>
                    <div class="nav-split"></div>
                    <div class="nav-app">
                    	<span>下载APP<i></i></span>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <div class="nav-tab">
    	<div class="nav-row">
        	<a class="nav-logo"><img src="http://yanxuan.nosdn.127.net/dbabd3aef45557e2df4512c0d3df53eb.gif?r=1495939534922"></a>
            <div class="nav-inner">
                <div class="nav-search">
                    <a class="nav-gouwu" href="#">
                        <i class="icon-gouwu-logo"></i>
                        <i class="icon-gouwu-shu">0</i>
                    </a>
                    <div class="nav-sousuo">
                        <div class="nav-sousuo-logo"><i class="nav-sousuo-icon"></i></div>
                        <div class="nav-sousuo-text">新疆长绒棉毛巾仅12元买送硬抽纸</div>
                        <input type="text" maxlength="100" autocomplete="off" class="nav-sousuo-input" value="" data-searchurl="#">
                    </div>
                </div>
                <ul class="tab-list">
                    <li class="tab-list-home">
                        <a class="tab-list-a" title="首页" href="#">首页</a>
                    </li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">居家</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">餐厨</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">配件</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">服装</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">洗护</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">婴童</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">杂货</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">饮食</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">志趣</a></li>
                    <li class="tab-list-split"></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">专题</a></li>
                    <li class="tab-list-item"><a class="tab-list-a" href="#">甄选家</a></li>
                </ul>
            </div>               
    	</div>
    </div>
    <div class="g-bd">
        <div class="g-bd-logo">
            <img class="js-img" src="http://yanxuan.nosdn.127.net/8329b0655bbf5b97ab3e149477a04067.jpg?imageView&amp;quality=95&amp;thumbnail=1920x480" alt="推荐 围巾特惠"> 
        </div>
    </div>
</body>
</html>
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
