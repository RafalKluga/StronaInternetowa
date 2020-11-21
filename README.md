

<html lang="pl">

<head>
<meta charset="utf-8"/>
<title>StronaInternetowa</title>
<link rel="stylesheet" href="main.css">
</head>
*{
margin:0px;
padding:0px;
}
h1{

font:bold 20px Tahoma;
}
h2{
font:bold 14px Tahoma;
}

header, section, footer, aside, nav, article, hgroup
{
display:block;
}

body{

width:100%;
display:-webkit-box;
-webkit-box-pack:center;
}

#big_wrapper
{
max-width:1000px;
margin:20px 0px;
display:-webkit-box;
-webkit-box-orient:vertical;
-webkit-box-flex:1;
}

#top_header
{
background:yellow;
border:3px solid black;
padding:20px;
}

#top_menu
{
border:red;
background:blue;
color:white;
}

#top_menu li
{
display:inline-block;
list-style:none;
padding:5px;
font:bold 14px Tahoma;
}

#new_div
{
display:-webkit-box;
-webkit-box-orient:horizontal;
}


#main_section
{
border:1px solid blue;
-webkit-box-flex:1;
margin:20px;
padding:20px;
}

#side_news
{
border:1px solid red;
width:220px;
margin:20px 0px;
padding:30px;
background:#66cccc;
}

#the_footer
{
text-align:center;
padding:20px;
border-top:2px solid green;
}

article{
background:#fffbcc;
border:1px solid red;
padding:20px;
margin-bottom:15px;
}

article footer
{
text-align:right;
}

<body>
<header>
  <h1 style="background-color:DodgerBlue;">Witam na mojej stronie</h1>
</header>

<nav>
<ul>
<li> Home</li>
<li> About Me</li>
<li> Mail</li>
</ul>
</nav>

<section>
To tu umieścimy całość strony - część główna strony
</section>

<aside>
<h4 style="background-color:Orange;">News</h4>
To tu będą umieszczane szybkie informacje
</aside>

<section id="main_section">

<article>
<header>
<hgroup>
<h1>Tytuł 1</h1>
<h2>Od czegoś trzeba zacząć</h2>
</hgroup>
</header>
<p>Pierwszy wpis !</p>
<footer>
<p> Napisał Jan Kowalski </p>
</footer>
</article>

<article>
<header>
<hgroup>
<h1>Tytuł 2</h1>
<h2>Od czegoś trzeba zacząć</h2>
</hgroup>
</header>
<p>Pierwszy wpis !</p>
<footer>
<p> Napisał Jan Kowalski </p>
</footer>
</article>


<footer>
Coś dla autorów
Copyright 2020
</footer>

</body>

</html>
