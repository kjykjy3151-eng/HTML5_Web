#기본 예제 6-6 배경 이미지 반복과 부착 형태, 위치 - 코드 6-20 (background_attachmentScroll.html)
<br>

<!DOCTYPE html>
<html>
<head>
    <title>CSS3 Background Property</title>
    <style>
        #box {
            background-color: #E7E7E8;
            background-image: url('BackgroundFront.png'), url('BackgroundBack.png');
            background-size: 100%;
            background-repeat: no-repeat;
            background-attachment: scroll;
        }
    </style>
</head>
<body>
<h1>Lorem ipsum dolor sit amet</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
<p>Proin ut quam feugiat, tincidunt dolor nec, iaculis dui.</p>
<p>Fusce elementum pretium diam vitae facilisis.</p>
<p>Mauris non lobortis lectus. Vestibulum a eros</p>
<p>Donec ultricies volutpat porttitor.</p>
</body>
</html>
