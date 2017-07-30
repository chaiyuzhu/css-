<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>盒子</title>
		<link rel="stylesheet" type="text/css" href="hz.css">	<!--css外联样式，href的值就是要加入的			css文件的地址-->
	</head>
	<body>
		<div id="page"><!--对页面整体的控制-->
			<div id="logo">
				<img src="tk/1.jpg" alt="一张风景图" width="100px">
			</div>
			<ul id="na">
				<li><a href="#" class="on">地址</a></li>
				<li ><a href="#">交通</a></li>
				<li><a href="#">预算</a></li>
				<li><a href="#">准备</a></li>
				<li><a href="#">时间</a></li>
			</ul>
			<p class="t2">
				<img src="tk/2.jpg" alt="一张图片" width="900px" height="300">
			</p>
			<p>带我去这个地方玩吧</p>
		</div>
	</body>
</html>

body{
	background-image: url("tk/3.jpg");
	font-size: 80%;
	font-family: "Courier New",Courier,monospace;
	letter-spacing: 0.15em;
}

#page{
	max-width: 940px;
	min-width: 720px;
	margin: 10px auto 10px auto;
	padding: 20px;
	border:4px double #000;
	background-color:rgba(100,100,100,0.6);
}

#logo{
	margin: 10px auto 25px auto;
	text-align: center;
}

ul{
	width: 570px;
	padding: 15px;
	margin :0px auto 0px auto;
	border-top: 2px solid pink;
	border-bottom: 2px solid pink;
	text-align: center;
}

li{
	display: inline;
	width: 600px;
	margin: 20px auto 20px auto;
	font-weight: normal;
	color: yellowgreen;
}

a{
	color: yellowgreen;
	text-transform: uppercase;
	text-decoration: none;
	padding: 6px 18px 5px 18px;
}

p.t2{
	text-align: center;
}

p{
	font-size: 20px;
	text-align: center;
}
