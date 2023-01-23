# Proposal
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>Love Expression</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="container">
		<div class="love">
			<h2>MARWA SALAAM, I<3U BEZZAF, <span>,CAN WE GET BACK TOGETHER, PLEASE :/, AND RELIVE ALL THE GOOD MOMENTS TOGETHER IN A NEW ADVENTURE, INCLUDING THE TRIP TO</span> KECH</h2>
			<a id="yes" href="yess.html">Yes</a>
			<a id="yes" href="yes.html">Yes</a>
		</div>
	</div>
</body>
</html>
*{
	padding: 0;
	margin: 0;
	outline:0;
}
.container{
	height: 100vh;
	width: 100vw;
	text-align:center;
	color:#333;
	background: pink;

}
.love,.yes,.no{padding-top: 15%;
		
		}
.love span{color:red;}
h2{font-size: 72px;margin-bottom: 20px;}
a{font-size: 24px;text-decoration: none;padding: 5px 10px;
	margin-top: 20px;border:3px solid #ddd; border-radius: 10px;}
#no{color:green; background: #eee;margin-right: 50px;}
#yes{color:green;background: #eee;}

.yes img{
	height: 30px;
	width: 30px;
	animation: image 4s linear infinite;
}
@keyframes image{
	0%{transform: scale(.5);}
	50%{transform: scale(1.5);}
	100%{transform: scale(.5);}
}
