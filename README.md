# web-assignment-1
Learning to work with html and css
<!DOCTYPE html>
<html lang="en">
<head>
	<title>Murfreesboro Regional Soccer League</title>
	<!--
		Murfreesboro Regional Soccer League main web page
		Filename: index.html

		Author: Muhammad Zahoor
		Date:2/15/17

		HTML5 and CSS3 Illustrated Unit D, Independent Challenge 2

		Supporting File:style.css
		Supporting File:modernizr.custom.62074.js
	-->

	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<script src="modernizr.custom.62074.js"></script>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="container">
		<header>
			<h1>Murfreesboro Regional Soccer League</h1>
			<p>Part of the North American Recreational Soccer Associtation</p>
		</header>
		<article>
			<p>The MRSL is open to player of all levels who want to play soccer in a relaxed, friendly environment.Even if you've never played soccer before, the MRSL is a great place to start.</p>
			<p>To get a feel for our league, we recommend you call us at the number below or stop by Davies Sporting Goods to talk to one or our coordinators and get the details on our next all team practice or workshop day. Then come kick around the ball with us and meet other players i the league.</p>
		</article>
		<aside>
			<h2>Upcoming Events</h2>
			<p>4/23</p>
			<p class="description">Open practice</p>
			<p>4/25</p>
			<p class="description">Blue/Green scrimmage</p>
			<p>5/1</p>
			<p class="description">Kids workshop</p>
			<p>5/2</p>
			<p class="description">Red/Yellow scrimmage</p>
			<p>5/5</p>
			<p class="description">Teens workshop (12-19)</p>
		</aside>
		<footer>
			<p>o/c Davies Sporting Goods</p>
			<p>418 N. Sartories St.</p>
			<p>Murfreesboro, TN 37130</p>
			<p>(615) 555-2255</p>
		</footer>
	</div>
</body>
</html>

CSS style sheet
/*

	Murfreesboro Regional Soccer League style sheet
	Filename:style.css

	Author:Muhammad Zahoor
	Date:2/15/17
	HTML5 and CSS3 Illustrated Unit D, Independent Challenge 2

	Supporting Files:none

*/


/* reset style */
article, aside, body, div, footer, header, h1, h2, p{
	border: 0;
	padding: 0;
	margin: 0;
}
/* body and page container */
.container{
	max-width: 640px;
	margin: 0 auto;
	border:3px solid black;
}
/* headings */
header{
	padding: 0.5em;
	text-align: center;
	color: white;
	background-color: green;
}
/* main content */
article{
	padding: 3%;
	width: 55%;
	float: right;
}
/* sidebar */
aside{
	padding: 2%;
	width: 35%;
	float: left;
	background-color: lightgreen;
}
aside h2{
	margin:0 0 0.4em;
}
aside p{
	margin: 0.4em 0;
}
aside p.description{
	margin-left: 1em;
}
/*footer section */
footer{
	padding: 0.5em;
	clear: both;
	color: white;
	background-color: black;
	text-align: right;
}
