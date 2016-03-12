<!DOCTYPE html>
<html lang="zh-cn">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>小洛洛可爱多</title>
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!--[if lt IE 9]>
    <script src="js/html5shiv.js"></script>
    <script src="js/respond.min.js"></script>
    <![endif]-->

    <style>

        body {
            padding-top: 50px;
            padding-bottom: 40px;
            color: #5a5a5a;
        }

        /* 轮播广告 */

        .carousel {
            height: 500px;
            margin-bottom: 60px;
        }

        .carousel .item {
            height: 500px;
            background-color: #000;
        }

        .carousel .item img {
            width: 100%;
        }

        .carousel-caption {
            z-index: 10;
        }

        .carousel-caption p {
            margin-bottom: 20px;
            font-size: 20px;
            line-height: 1.8;
        }

        /* 简介 */

        .summary {
            padding-right: 15px;
            padding-left: 15px;
        }

        .summary .col-md-4 {
            margin-bottom: 20px;
            text-align: center;
        }

        /* 特性 */

        .feature-divider {
            margin: 40px 0;
        }

        .feature {
            padding: 30px 0;
        }

        .feature-heading {
            font-size: 50px;
            color: #2a6496;
        }

        .feature-heading .text-muted {
            font-size: 28px;
        }

        /* 响应式布局 */

        @media (max-width: 768px) {

            .summary {
                padding-right: 3px;
                padding-left: 3px;
            }

            .carousel {
                height: 300px;
                margin-bottom: 30px;
            }

            .carousel .item {
                height: 300px;
            }

            .carousel img {
                min-height: 300px;
            }

            .carousel-caption p {
                font-size: 16px;
                line-height: 1.4;
            }

            .feature-heading {
                font-size: 34px;
            }

            .feature-heading .text-muted {
                font-size: 22px;
            }
        }

        @media (min-width: 992px) {
            .feature-heading {
                margin-top: 120px;
            }
        }
    </style>

</head>

<body>
<!-- 顶部导航 -->
<div class="navbar navbar-inverse navbar-fixed-top" role="navigation" id="menu-nav">
    <div class="container">
        <div class="navbar-header">
            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                <span class="sr-only"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#">小洛洛的简历</a>
        </div>
        <div class="navbar-collapse collapse">
            <ul class="nav navbar-nav">
            <!-- 
                <li class="active"><a href="#ad-carousel">关于我</a></li>
                 -->
                <!-- 
                <li><a href="#summary-container">简述</a></li>
                 -->
                <li class="dropdown">
                    <a href="#" class="dropdown-toggle" data-toggle="dropdown">技能 <span class="caret"></span></a>
                    <ul class="dropdown-menu" role="menu">
                        <li><a href="#feature-tab" data-tab="tab-chrome">Java基础</a></li>
                        <li><a href="#feature-tab" data-tab="tab-firefox">Web前端</a></li>
                        <li><a href="#feature-tab" data-tab="tab-safari">数据库</a></li>
                        <li><a href="#feature-tab" data-tab="tab-opera">框架</a></li>
                        <li><a href="#feature-tab" data-tab="tab-ie">Linux</a></li>
                    </ul>
                </li>
                <li><a href="#" data-toggle="modal" data-target="#about-modal">关于我</a></li>
            </ul>
        </div>
    </div>
</div>


<!-- 广告轮播 -->
<div id="ad-carousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#ad-carousel" data-slide-to="0" class="active"></li>
        <li data-target="#ad-carousel" data-slide-to="1"></li>
        <li data-target="#ad-carousel" data-slide-to="2"></li>
        <li data-target="#ad-carousel" data-slide-to="3"></li>
        <li data-target="#ad-carousel" data-slide-to="4"></li>
    </ol>
    <div class="carousel-inner">
        <div class="item active">
            <img src="images/whoam.png" alt="1 slide">

            <div class="container">
                <div class="carousel-caption">
                <!--  
                    <h1></h1>

                    <p>Google Chrome，又称Google浏览器，是一个由Google（谷歌）公司开发的网页浏览器。</p>
				
                    <p><a class="btn btn-lg btn-primary" href="http://www.google.cn/intl/zh-CN/chrome/browser/"
                          role="button" target="_blank">点我下载</a></p>
                          -->
                </div>
            </div>
        </div>
        <div class="item">
            <img src="images/movie1.png" alt="2 slide">

            <div class="container">
                <div class="carousel-caption">
                <!-- 
                    <h1>Firefox</h1>

                    <p>Mozilla Firefox，中文名通常称为“火狐”或“火狐浏览器”，是一个开源网页浏览器。</p>

                    <p><a class="btn btn-lg btn-primary" href="http://www.firefox.com.cn/download/" target="_blank"
                          role="button">点我下载</a></p>
                 -->
                </div>
            </div>
        </div>
        <div class="item">
            <img src="images/movie2.png" alt="3 slide">

            <div class="container">
                <div class="carousel-caption">
                <!-- 
                    <h1>Safari</h1>

                    <p>Safari，是苹果计算机的最新操作系统Mac OS X中的浏览器。</p>

                    <p><a class="btn btn-lg btn-primary" href="http://www.apple.com/cn/safari/" target="_blank"
                          role="button">点我下载</a></p>
                    --> 
                </div>
            </div>
        </div>
        <div class="item">
            <img src="images/movie3.png" alt="4 slide">

            <div class="container">
                <div class="carousel-caption">
                <!-- 
                    <h1>Opera</h1>

                    <p>Opera浏览器，是一款挪威Opera Software ASA公司制作的支持多页面标签式浏览的网络浏览器。</p>

                    <p><a class="btn btn-lg btn-primary" href="http://www.opera.com/zh-cn" target="_blank"
                          role="button">点我下载</a></p>
               --> 
                </div>
            </div>
        </div>
        <div class="item">
            <img src="images/movie4.png" alt="5 slide">

            <div class="container">
                <div class="carousel-caption">
                 <!-- 
                    <h1>IE</h1>

                    <p>Internet Explorer，简称 IE，是微软公司推出的一款网页浏览器。</p>

                    <p><a class="btn btn-lg btn-primary" href="http://ie.microsoft.com/" target="_blank"
                          role="button">点我下载</a></p>
                  --> 
                </div>
            </div>
        </div>
    </div>
    <a class="left carousel-control" href="#ad-carousel" data-slide="prev"><span
            class="glyphicon glyphicon-chevron-left"></span></a>
    <a class="right carousel-control" href="#ad-carousel" data-slide="next"><span
            class="glyphicon glyphicon-chevron-right"></span></a>
</div>


<!-- 主要内容 -->
<div class="container summary">

    <!-- 简介 -->
    <div class="row" id="summary-container">
        <div class="col-md-4">
            <img class="img-circle" src="images/a1.jpg" alt="chrome">

            <h2>Java基础</h2>

            <p>熟悉Java语言和面向对象设计方法</p>
		<!-- 
            <p><a class="btn btn-default" href="#" role="button">点我下载</a></p>
         -->
        </div>
        <div class="col-md-4">
            <img class="img-circle" src="images/a2.jpg" alt="firefox">

            <h2>Web前端</h2>

            <p>HTML、CSS、JS、AJAX,Bootstrap等前端技术</p>
		<!-- 
            <p><a class="btn btn-default" href="#" role="button">点我下载</a></p>
         -->
        </div>
        <div class="col-md-4">
            <img class="img-circle" src="images/a3.png" alt="safari">

            <h2>框架</h2>

            <p>Struts2、Spring、SpringMVC、Hibernate、Mybatis</p>

		<!-- 
            <p><a class="btn btn-default" href="#" role="button">点我下载</a></p>
         -->
        </div>
    </div>

    <!-- 特性 -->

    <hr class="feature-divider">

    <ul class="nav nav-tabs" role="tablist" id="feature-tab">
        <li class="active"><a href="#tab-chrome" role="tab" data-toggle="tab">Java基础</a></li>
        <li><a href="#tab-firefox" role="tab" data-toggle="tab">Web前端</a></li>
        <li><a href="#tab-safari" role="tab" data-toggle="tab">数据库</a></li>
        <li><a href="#tab-opera" role="tab" data-toggle="tab">框架</a></li>
        <li><a href="#tab-ie" role="tab" data-toggle="tab">Linux</a></li>
    </ul>

    <div class="tab-content">
        <div class="tab-pane active" id="tab-chrome">
            <div class="row feature">
                <div class="col-md-7">

                    <h2 class="feature-heading">Java基础 <span
                            class="text-muted">必不可少的基本功</span></h2>

                    <p class="lead">熟练掌握Java基础知识，熟悉OOP编程</p>
                </div>
                <div class="col-md-5">
                    <img class="feature-image img-responsive" src="images/y1.jpg"
                         alt="Chrome">
                </div>
            </div>
        </div>
        <div class="tab-pane" id="tab-firefox">
            <div class="row feature">
                <div class="col-md-5">
                    <img class="feature-image img-responsive" src="images/y2.jpg"
                         alt="Firefox">
                </div>
                <div class="col-md-7">

                    <h2 class="feature-heading">Web前端 <span class="text-muted">色彩缤纷的网页</span>
                    </h2>

                    <p class="lead">熟悉HTML、CSS、JavaScript、JQuery、Ajax、Bootstrap等前端技术</p>
                </div>
            </div>
        </div>
        <div class="tab-pane" id="tab-safari">
            <div class="row feature">
                <div class="col-md-7">

                    <h2 class="feature-heading">数据库 <span class="text-muted">海量数据存储</span></h2>

                    <p class="lead">熟悉Oralce及 MySQL数据库，熟悉数据库的常用命令</p>
                </div>
                <div class="col-md-5">
                    <img class="feature-image img-responsive" src="images/c1.jpg"
                         alt="Safari">
                </div>
            </div>
        </div>
        <div class="tab-pane" id="tab-opera">
            <div class="row feature">
                <div class="col-md-5">
                    <img class="feature-image img-responsive" src="images/y3.png"
                         alt="Opera">
                </div>
                <div class="col-md-7">

                    <h2 class="feature-heading">框架 <span class="text-muted">企业开发利器</span>
                    </h2>

                    <p class="lead">熟悉Struts2、Spring、SpringMVC、Hibernate、Mybatis框架</p>
                </div>
            </div>
        </div>
        <div class="tab-pane" id="tab-ie">
            <div class="row feature">
                <div class="col-md-7">

                    <h2 class="feature-heading">Linux <span class="text-muted">程序猿必用的操作系统</span></h2>

                    <p class="lead">熟悉Linux 常用命令，目前正在学习Linux...</p>
                </div>
                <div class="col-md-5">
                    <img class="feature-image img-responsive" src="images/c2.jpg"
                         alt="IE">
                </div>
            </div>
        </div>
    </div>

    <!-- 关于 -->
    <div class="modal fade" id="about-modal" tabindex="-1" role="dialog" aria-labelledby="modal-label"
         aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal"><span
                            aria-hidden="true">&times;</span><span class="sr-only">关闭</span></button>
                    <h4 class="modal-title" id="modal-label">我的基本信息：</h4>
                </div>
                <div class="modal-body">
                    <p>我叫梁孟洛，95年，雄性。毕业于郑州大学工学院，计算机多媒体专业。毕业后在北大青鸟参加了为期6个月的系统培训，期望找到一个Java软件工程师的工作，
                    期望的工作地点是：北京(其他城市也可考虑)，期望的薪资是：5000</p>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default" data-dismiss="modal">雇佣了！</button>
                </div>
            </div>
        </div>
    </div>


    <footer>
        <p class="pull-right"><a href="#top">回到顶部</a></p>

        <p> 2016 - 03 - 12 </p>
    </footer>

</div>

<script src="js/jquery-1.11.1.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script>
    $(function () {
        $('#ad-carousel').carousel();
        $('#menu-nav .navbar-collapse a').click(function (e) {
            var href = $(this).attr('href');
            var tabId = $(this).attr('data-tab');
            if ('#' !== href) {
                e.preventDefault();
                $(document).scrollTop($(href).offset().top - 70);
                if (tabId) {
                    $('#feature-tab a[href=#' + tabId + ']').tab('show');
                }
            }
        });
    });
</script>
</body>
</html>
