<!DOCTYPE html>
<html>

<head>
    <meta charset='utf-8'>
    <title>Document</title>

<body>
    <img src="./public/musk.jpg" style="width: 300px; 
    display: block;
    margin-left: auto;
    margin-right: auto;" />
    <h3 style="font-family: 'nanumsquare';
     letter-spacing: -4px;
     text-align: center;">hojun 차호준</h3>
    <p><strong style="color: red;">Frontend</strong> developer</p>

</body>

</html>

<!-- 이미지 가운데 정렬 
display: block;
margin-left: auto;
margin-right: auto;


    <img src="./public/musk.jpg" style="width: 300px; 
        display: block;
        margin-left: auto;
        margin-right: auto;" />

폰트
color: 글자 색, 'red' 또는 #eee(hex값) 처럼 설정 가능
자간
letter-spacing: -4px 처럼 조절 가능. 양의 값(넓어짐). 음의 값은 좁아짐.
폰트 종류
font-family: 'gulim' 또는 'nanumsquare' 처럼 시스템에 설치돼 있는 폰트 사용 가능
폰트 크기
vw: 현재 브라우저의 너비를 뜻한다.
%: 해당 태그를 감싸고 있는 부모 태그 사이즈에 비례하여 크기를 조정한다는 뜻

글자를 굵게 하려면 
font-weight: 100 ~ 900 사이에 가능. 근데 폰트가 굵기를 지원해야 한다.
    <p><span style="color: red; font-weight: 900;">Frontend</span> developer</p>
간편하게 하려면 <strong>으로 감싸면 된다.
    <p><strong style="color: red;">Frontend</strong> developer</p>

span태그: 글자를 감쌀 수 있는 별 의미 없는 태그. 범위 조절에 사용
    <p><span style="color: red;">Frontend</span> developer</p>


-->

HTML 파일에 CSS 파일 불러오기
    <link href="경로" rel="stylesheet">
<head>
    <meta charset='utf-8'>
    <title>Document</title>
    <link href="./css/index.css" rel="stylesheet">
</head>

