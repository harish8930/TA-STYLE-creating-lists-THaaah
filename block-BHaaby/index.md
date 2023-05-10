html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>list item</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="navbar">
  <div class="container1 flex">           
    <nav>
      <ul class="flex nav-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
<li><a href="#">FaQs</a></li>
<li><a href="#">Program</a></li>
<li><a href="#">Contact</a></li>
</ul>
  </nav>
</div>
</header>
<div class="container2">
  <div class="box1">
<ol>
  <li>Home</li>
  <li>Page</li>
  <li>Services</li>
  <li>About Us</li>
  <ol start="20">
  <li>Portfolio</li>
  <li>News</li>
  <li>Testimonial</li></ol>
</ol>
  </div>
  <div class="box2">
<ul>
<li>Home</li>
<li>Menu</li>
<ol>
  
  <li>Menu1</li>
<ul><li>Sub Menu1</li>
<li>Sub Menu2</li>
</ul>
<li>Menu2</li>
<Li>Menu3</Li>
<li>Menu4</li>
<li>Menu5</li>
</ol>
<li>How We Work</li>
<li>Contact Us </li>
</ul>
  </div>



</body>
</html>
    
  style.css
 
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;}



	/*start*/
body{background-color: rgb(228, 228, 189);}


.navbar{width: 100%;   
background-color: orange;
height: 40px;
}


.flex{display: flex;
	flex-direction: row;
}

li, a{ margin-right: 10px;  
color: white;
text-decoration: none;
margin-top: 10px;
}
.container1{margin-left: 100px;
}


.container2{ display: flex;
	flex-direction: row;
	

}


.box1, .box2, .box3{
	width: 200px;
	height: 300px;
	background-color:rgb(22, 120, 185);
margin: 10px 30px 0px 100px;
box-shadow: 2px 2px 2px 2px;
}

ol{list-style-type: decimal;
list-style-position: inside;

}
ul{list-style-type: disc;
list-style-position: inside;
}

 ......
  
  
  
  
  
  
  
