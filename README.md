<!DOCTYPE html>
<html>
<head>
<title>Contoh CSS Website Layout</title>
<style>
    body {
margin: 0;
}
.header {
background-color: #f1f1f1;
padding: 20px;
text-align: center;
}
.topnav {
overflow: hidden;
background-color: #333;
}
.topnav a {
float: left;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
.topnav a:hover {
background-color: #ddd;
color: black;
}
* {
box-sizing: border-box;
}
.column {
float: left;
width: 33.33%;
padding: 15px;
}
.row:after {
content: "";
display: table;
clear: both;
}
@media screen and (max-width:600px) {
.kolom {
width: 100%;
}
}
* {
box-sizing: border-box;
}
body {
margin: 0;
}
.header {
background-color: #f1f1f1;
padding: 20px;
text-align: center;
}
ul {
list-style-type: none;
margin: 0;
padding: 0;
overflow: hidden;
background-color: #333;
}
li {
float: left;
}
li a, .dropbtn {
display: inline-block;
color: white;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
li a:hover, .dropdown:hover .dropbtn {
background-color: red;
}
li.dropdown {
display: inline-block;
}
.dropdown-content {
display: none;
position: absolute;
background-color: #f9f9f9;
min-width: 160px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}
.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
text-align: left;
}
.dropdown-content a:hover {background-color: #f1f1f1;}
.dropdown:hover .dropdown-content {
display: block;
}
.topnav {
overflow: hidden;
background-color: #333;
}
.topnav a {
float: left;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
.topnav a:hover {
background-color: #ddd;
color: black;
}
.column {
float: left;
padding: 10px;
}
.column.side {
width: 25%;
}
.column.middle {
width: 50%;
}
.row:after {
content: "";
display: table;
clear: both;
}
@media screen and (max-width: 600px) {
.column.side, .column.middle {
width: 100%;
}
}
.footer {
background-color: #f1f1f1;
padding: 10px;
text-align: center;
}
    </style>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<div class="header">
<h1>Header</h1>
</div>
<ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#news">News</a></li>
    <li class="dropdown">
    <a href="#" class="dropbtn">Dropdown</a>
    <div class="dropdown-content">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
    </div>
    </li>
    </ul>    
<div class="row">
<div class="column side">
<h2>Diri saya</h2>
<p>Saya Naba Izza Alghani 
    Jurusan Teknologi Informasi 
    NPM saya adalah 2024806047 
    saya sedang belajar membuat tampilan layout</p>
</div>
<div class="column middle">
<h2>Diri saya</h2>
<p>Saya Naba Izza Alghani 
    Jurusan Teknologi Informasi 
    NPM saya adalah 2024806047 
    saya sedang belajar membuat tampilan layout</p>
</div>
<div class="column side">
<h2>Diri saya</h2>
<p>Saya Naba Izza Alghani 
    Jurusan Teknologi Informasi 
    NPM saya adalah 2024806047 
    saya sedang belajar membuat tampilan layout</p>
</div>
</div>
<div class="footer">
    <p>Footer</p>
    </div>
    
</body>
</html>
