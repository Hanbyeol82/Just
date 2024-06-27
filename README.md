# Just
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>사진 전시</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFFFFF;
            color: #000000;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8A94FF;
            color: #FFFFFF;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .intro {
            margin: 20px 0;
            padding: 20px;
            background-color: #F0F0F0;
            border-radius: 10px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .gallery img {
            max-width: 100%;
            height: auto;
            border: 2px solid #8A94FF;
            border-radius: 5px;
        }
        .social {
            text-align: center;
            margin: 20px 0;
        }
        .social a {
            margin: 0 10px;
            color: #8A94FF;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>사진 전시</h1>
    </header>
    <div class="container">
        <div class="intro">
            <h2>소개글</h2>
            <p>여기에 소개글을 작성하세요. 예를 들어, 본인의 사진 전시에 대한 설명이나 작품에 대한 간단한 소개를 작성할 수 있습니다.</p>
        </div>
        <div class="gallery">
            <img src="사진1.jpg" alt="사진 1">
            <img src="사진2.jpg" alt="사진 2">
            <img src="사진3.jpg" alt="사진 3">
            <!-- 추가 사진들을 여기에 넣으세요 -->
        </div>
        <div class="social">
            <h2>소셜 미디어</h2>
            <a href="https://www.instagram.com/yourprofile" target="_blank">Instagram</a>
            <a href="https://www.facebook.com/yourprofile" target="_blank">Facebook</a>
            <a href="https://www.twitter.com/yourprofile" target="_blank">Twitter</a>
            <!-- 추가 소셜 미디어 링크를 여기에 넣으세요 -->
        </div>
    </div>
</body>
</html>
