<!DOCTYPE html>
<html>
<head>
	<title>Basic Tags</title>
	<!--Loading fonts-->
	<link href='https://fonts.googleapis.com/css?family=Sanchez' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=Noto+Serif' rel='stylesheet' type='text/css'>
	<!--Done Loading fonts-->
	<style type="text/css">
		body {
			margin: 0px 0px;
			padding-left: 0px 0px;
		}
		#logo {
			padding: 30px 0px;
			width: 100%;
			text-align: center;
			 /* CSS3 Transition elements */ 
  			-webkit-transition: color 4s;
			-moz-transition: color 4s;
      		-o-transition: color 4s;
  			transition: color 4s;
		}
			#logo:hover #top{
				color: #26b3ef;
			}
			#logo:hover #middle { 
				color: #26b3ef;
			}
			
			#logo:hover #bottom { 
				color: #26b3ef;
			}
			#top {
				margin: 0px;
				font-family: 'Sanchez', serif;
				font-size: 35px;
				-webkit-transition: color 4s;
				-moz-transition: color: 4s;
      			-o-transition: color 4s;
  				transition: color 4s;
			}
			#middle {
				margin: 0px;
				font-family: 'Sanchez', serif;
				font-weight: 900;
				font-size: 45px;
				-webkit-transition: color 4s;
				-moz-transition: color 4s;
      			-o-transition: color 4s;
  				transition: color 4s;
			}
			#bottom {
				margin: 0px;
				font-family: 'Sanchez', serif;
				font-weight: 600;
				font-size: 30px;
				-webkit-transition: color 4s;
				-moz-transition: color 4s;
      			-o-transition: color 4s;
  				transition: color 4s;
		}
		#hr_1 {
			height: 3px;
			background-color: black;
		}
		#hr_2 {
			height: 2px;
			background-color: black;
		}
		nav {
			margin: 20px 0px; 
			width: 100%;
			text-align: center;
			-webkit-transition: background-color 4s;
			-moz-transition: background-color 4s;
      		-o-transition: background-color 4s;
  			transition: background-color 4s;
		}
			nav:hover {
				background-color: #ffffff;
			}
			nav a {
				font-family: 'Sanchez', serif;
				text-decoration: none;
				color: #555;
				padding: 10px 30px;
				font-size: 16px;
				-webkit-transition: color 4s;
	  			transition: color 4s;
			}
			nav a:hover {
				color: #333333;
			}
		
		.images {
			background-color: white;
			width: 100%;
			text-align: center;
		}
			.images img {
				opacity: 1.0; 
				-webkit-transition: opacity 0.3s;
				-moz-transition: opacity 0.3s;
      			-o-transition: opacity 0.3s;
  				transition: opacity 0.3s;
		}
			.images img:hover {
				opacity: 0.3;
		}
		
		p {
			border-radius: 20px;
			padding: 20px;
			background-color:white;
			color: black;
			text-align: center;
			font-size: 17px;
			font-family: 'Noto Serif', serif;
		}
	</style>
</head>
<body>
	<header>
		<div id="logo">
			<div id="top">Explorer Countries</div>
		</div>
		<nav>
			  <hr id="hr_1">
			  <br>
			  <a href="#">Home</a> 
		      <a href="#">About</a> 
  			 <a href="#">Plan1</a> 
   			  <a href="#">Plan2</a>
   			  <a href="#">Plan3</a>
   			  <br>
   			  <br>
   			  <hr id="hr_2">
 		</nav>
	</header>
	<div class="images">
			<img src="fist.jpg" alt="fist">
			<img src="fist.jpg" alt="fist">
			<img src="fist.jpg" alt="fist">
	</div>
	<br>
	<p>At Explorer, we specialize in small group adventure holidays, with over 500 trips on offers in 120 countries. We have a wide range of adventure travel options including walking and trekking tours, cycling tours, polar voyages, family adventure holidays and much more... <br> Reowned for its rainforest jungles filled with bird and monkey species as wells as its white sandy beaches and steaming volcanoes. Costa Rica packs in...</p>
</body>
</html>
