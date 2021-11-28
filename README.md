<!doctype html>
<html lang="zh-cn">
<head>
    <meta charset="utf-8">
    <!--移动端适配-->
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="./css/bootstrap.css">
    <link rel="stylesheet" href="./css/mycss.css">
    <script src="./js/jquery-3.5.1.js"></script>
    <script src="./js/bootstrap.bundle.js"></script>
    <script src="./js/bootstrap.min.js"></script>
    <title>ずっと真夜中でいいのに FSANS CLUB</title>
    <link rel="icon" href="./img/logo_fc.png" sizes="16x16">
    <style>
        body {
            animation: fadeInAnimation ease 0.5s;
            animation-iteration-count: 1;
            animation-fill-mode: forwards;
        }
        @keyframes fadeInAnimation {
            0% {
                opacity: 0.5;
            }
            100% {
                opacity: 1;
            }
        }
    </style>
    <script>
        function home(){
            location.href = "Mid.html";
        }
    </script>
</head>
<body>
<div id="Top">
<img src="./img/logo_fc.png" alt="" left=0px width="48" height="27">
   <div left="100" >
    <img src="./img/LOGO.png" position="absolute" alt="" >
   </div>
</div>

<div id="Banner">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="./img/background1.png" class="d-block w-100 h-25" alt="">
            </div>
            
            <div class="carousel-item">
                <img src="./img/background2.png" class="d-block w-100 h-25" alt="">
            </div>
            <div class="Text">
                <p><b>ずっと真夜中でいいのに</b></p>
            </div>
        
            <div class="button">
                <button type="button" class="btn btn-secondary btn-lg" onclick="home()">进入首页</button>
            </div>
        </div>
    </div>
</div>
<div id="Bottom">
    ずっと真夜中でいいのに FANS CLUB
</div>
<!--JS控件-->
<script src="./js/jquery-3.5.1.js"></script>
<script src="./js/bootstrap.bundle.js"></script>
<script src="./js/bootstrap.min.js"></script>
</body>
</html>
