#기본 예제 6-16 글자와 박스에 그림자 생성 - 코드 6-50 (shadow_duplication.html)
<br>

<!DOCTYPE html>
<html>
<head>
    <title>CSS3 Property Basic</title>
    <style>
        .box {
            border: 3px solid black;
            box-shadow: 10px 10px 10px black, 10px 10px 20px orange, 10px 10px 30px red;
            text-shadow: 10px 10px 10px black, 10px 10px 20px orange, 10px 10px 30px red;
        }
    </style>
</head>
<body>
    <div class="box">
        <h1>Lorem ipsum dolor amet</h1>
    </div>
</body>
</html>
