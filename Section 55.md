#기본 예제 6-4 display 속성 - 코드 6-13 (display_inline-blockWithMargin.html)
<br>

<!DOCTYPE html>
<html>
<head>
    <title>CSS3 Display Property</title>
    <style>
        #box {
            display: inline-block;
            background-color: red;
            width: 100px; height: 50px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <p>의미 없는 더미 객체</p>
    <span>더미 객체</span>
    <div id="box">대상 객체</div>
    <span>더미 객체</span>
    <p>의미 없는 더미 객체</p>
</body>
</html>
