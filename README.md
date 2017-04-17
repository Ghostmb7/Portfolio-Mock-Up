# Portfolio-Mock-Up
Here is the code to a portfolio mock up I made. I've already designed my portfolio site. Here is something we can play around with!


HTML
<!Doctype HTML>
<title>Portfolio</title>
</head>
<ul>
<li><a href='#about'/>About</a></li>
<li><a href='#portfolio'/>Portfolio</a></li>
<li><a href='#designs'/>Designs</a></li>
</ul>

<br />
<br />
<br />
<br />

<body>
<div id='wrap'>

<img src='https://scontent-atl3-1.xx.fbcdn.net/v/t1.0-9/17523672_10212168210617130_395292826014727769_n.jpg?oh=72764154122ed07c8a39c01d4abf961f&oe=594D5728' width='250'/>
</div>

<div>
<h1 id='about'></h1>

<h2>Front-End Web Developer</h2>

<br />

<h2>Graphic Designer</h2>

<br />

<h2>Theme Developer</h2>

</div>

<div>

<h1>About</h1>
<h2>I'm a front-end web developer/Graphic designer whom blogs and trains martial arts on the side. I can also develop your webite's theme as well as cover website maitenance for you! </h2>

</div>

<br />

<div>

<h1 id='portfolio'>Portfolio</h1>
<a href='http://www.ruralhs.org/'/><img src='https://res.cloudinary.com/dycjxv4nv/image/upload/v1491323383/unnamed_pgcsma.jpg' width='450'/></a>

</div>
<br />
<br />


<h1 id='designs'>Designs</h1>
<img src='https://res.cloudinary.com/dycjxv4nv/image/upload/v1491323383/unnamed_pgcsma.jpg' width='350'/>

<br />
<br />
<br />
<br />

<div>

<h1>Faqs</h1>
<h2>What can I bring to the table?</h2>
<p>With a little less than a year of experience in web design you will find that I can work with a team or independently to complete your websites satisfaction.</p>
</div>

<div>
<h2>What languages do I know?</h2>
<p>I am proficient with HTML, CSS, Javascript/Jquery, and PHP. I aslo use bootstrap and wordpress frame works.</p>
</div>

<div>
<h2>How long does it take to create a website</h2>
<p>That depends on your request. A simple one page website can take a couple of days while a complex 7 page website can take weeks or even months. It all depends on what you want your site to do. I will get it done as fast as humanly possible though!</p>
</div>

<br />
<br />
<br />

<div id='connect'>

<h4>Connect</h4>
<a href='https://www.facebook.com/marquis.royal1'/><img src='C:\Users\emc1r\Documents\portfolio\pics\facebook.png' width='50' margin='25'/></a>
<a href=''/><img src='C:\Users\emc1r\Documents\portfolio\pics\gmail_256.png'width='50' margin='25'/></a>
<a href='https://twitter.com/Royal1000'/><img src='C:\Users\emc1r\Documents\portfolio\pics\twitter.png' width='50' margin='25'/></a>
<a href='https://www.instagram.com/royalmarquis/'/><img src='C:\Users\emc1r\Documents\portfolio\pics\instagram.png' width='50' margin='25'/></a>

</div>

<br />

<footer>
<h5>&copy 2017 by Echo Nova </h5>
</footer>
</body>
<!Doctype html>

CSS

body{
	background-color:#D3D3D3;
	font-family:Brush Script MT;
	font-size:24px;
}

ul{
	background-color:black;
	height:50px;
	width:auto;
	margin:0px;
	color:white;
	position:fixed;
	text-align:center center;
	list-style-type:none;
}

li{
	width:150px;
	float:left;
	border-right:1px solid white;
	text-align:center;
	margin-left:195px;
	padding-top:15px;
	padding:10px;
}

a{
	color:white;
}
 
 h1{
	 font-family:Brush Script MT;
 }
 
 #wrap{
	 float:left;
	 margin:25px;
 }
 
 footer{
	 text-align:center;
 }
 
 #connect{
	 background-color:black;
	 color:white;
	 height:130px;
	 width:auto;
	 margin:auto;
 }
