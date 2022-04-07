# Rubato-menu

# 프로그램 설명
이 프로그램에 사용한 소프트웨어 : 비주얼 스튜디오 코드 : <b> html5 + css + jquary <b>

# 구현 화면
(1) 첫화면 
![image](https://user-images.githubusercontent.com/81358269/161183879-f66ad895-c157-4a9e-b5c7-6f1cd98f2e1b.png)

# html 
    
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rubato 0407</title>
    <link rel="stylesheet" href="./css/style.css">
    <script src="./script/jquery-1.12.3.js" defer ></script>
    <script src="./script/script.js" defer ></script>
</head>
<body>
    <div id="page">
        <header>
            <div id="logo"><img src="./images/logo.png" alt="로고">
            </div>
            <div id="top">
                <div class="main-menu">
                    <li>
                        <a href="#">탑</a>
                        <ul class="sub">
                            <li><a href="#">블라우스</a></li>
                            <li><a href="#">티</a></li>
                            <li><a href="#">셔츠</a></li>
                            <li><a href="#">니트</a></li>
                        </ul>
                    </li>
                <li>
                    <a href="#">아우터</a>
                    <ul class="sub">
                        <li><a href="#">자켓</a></li>
                        <li><a href="#">코트</a></li>
                        <li><a href="#">가디건</a></li>
                        <li><a href="#">머플러</a></li>
                    </ul>
                </li>
                <li>
                    <a href="#">팬츠</a>
                    <ul class="sub">
                        <li><a href="#">청바지</a></li>
                        <li><a href="#">짧은치마</a></li>
                        <li><a href="#">긴바지</a></li>
                        <li><a href="#">레깅스</a></li>
                    </ul>
                </li>
                <li>
                    <a href="#">악세서리</a>
                    <ul class="sub">
                        <li><a href="#">귀고리</a></li>
                        <li><a href="#">목걸이</a></li>
                        <li><a href="#">반지</a></li>
                        <li><a href="#">팔찌</a></li>
                    </ul>
                </li>
                </div>
            </div>
        </header>
        <div class="clear"></div>
        <section>
            <div class="imgs">
                <img src="./images/main_img.png" alt="">
                <img src="./images/main_img2.png" alt="">
                <img src="./images/main_img3.png" alt="">
                <img src="./images/main_img4.png" alt="">
                <img src="./images/main_img5.png" alt="">
            </div>
        </section>
        <aside>
            <ul>
                <li><img src="./images/banner01.png" alt=""></li>
                <li><img src="./images/banner02.png" alt=""></li>
            </ul>
        </aside>
        <div class="clear"></div>
        <footer>
            <div id="address">
                <img src="./images/address.png" alt=""></div>
            <div id="customer">
                <img src="./images/customer.png" alt="">
            </div>
        </footer>
        <div class="clear"></div>
    </div>
</body>
</html>

