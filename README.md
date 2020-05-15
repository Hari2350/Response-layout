# Response-layout
<!DOCTYPE html>
<html>
<meta charset="utf-8">
<title>Response Layout</title>
<style>

*{
	box-sizing: border-box;
}
h2 {
	margin-bottom: 20px;
	text-align: center;
}
p.ch{
	border:1px solid black;
	background-color: #FFCCCB;
	float:right;
	margin-top: 0px;
}

p.be{
	border:1px solid black;
	background-color:red;
	color: white;
	float: right;
	margin-top: 0px;
}
p.su{
	border:1px solid black;
	background-color:#FFFACD;
	float: right;
	margin-top: 0px;
}

div.fix{
    border:1px solid black;
    background-color:#BA55D3;
    width:50%;
    height: 250px;
    margin-left: 100px;
    color: black; 
}


.row{
	width:100%;
}

@media(min-width: 992px){
   .col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-4,
   .col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,
   .col-lg-11,.col-lg-12{
   	float: left;
   	border: 1px black;
   }
   .col-lg-1 {
   	 width: 8.33%;
   }
   .col-lg-2 {
   	 width: 16.66%;
   }
   .col-lg-3 {
   	 width: 25%;
   }
   .col-lg-4 {
   	 width: 33%;
   }
   .col-lg-5 {
   	 width: 42%;
   }
   .col-lg-6 {
   	 width: 50%;
   }
   .col-lg-7 {
   	 width: 58.33%;
   }
   .col-lg-8 {
   	 width: 66.66%;
   }
   .col-lg-9 {
   	 width: 74.99%;
   }
   .col-lg-10 {
   	 width: 83.33%;
   }
   .col-lg-11 {
   	 width: 91.66%;
   }
   .col-lg-12 {
   	 width: 100%;
   }
}

@media(min-width: 768px) and (max-width: 991px){
   .col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-4,
   .col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,
   .col-md-11,.col-md-12{
   	float: left;
   	border: 1px black;
   }
   .col-md-1 {
   	 width: 8.33%;
   }
   .col-md-2 {
   	 width: 16.66%;
   }
   .col-md-3 {
   	 width: 25%;
   }
   .col-md-4 {
   	 width: 33%;
   }
   .col-md-5 {
   	 width: 42%;
   }
   .col-md-6 {
   	 width: 50%;
   }
   .col-md-7 {
   	 width: 58.33%;
   }
   .col-md-8 {
   	 width: 66.66%;
   }
   .col-md-9 {
   	 width: 74.99%;
   }
   .col-md-10 {
   	 width: 83.33%;
   }
   .col-md-11 {
   	 width: 91.66%;
   }
   .col-md-12 {
   	 width: 100%;
   }
}

@media(max-width: 767px){
   .col-sm-1,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-4,
   .col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9,.col-sm-10,
   .col-sm-11,.col-sm-12{
   	float: left;
   	border: 1px black;
   }
   .col-sm-1 {
   	 width: 8.33%;
   }
   .col-sm-2 {
   	 width: 16.66%;
   }
   .col-sm-3 {
   	 width: 25%;
   }
   .col-sm-4 {
   	 width: 33%;
   }
   .col-sm-5 {
   	 width: 42%;
   }
   .col-sm-6 {
   	 width: 50%;
   }
   .col-sm-7 {
   	 width: 58.33%;
   }
   .col-sm-8 {
   	 width: 66.66%;
   }
   .col-sm-9 {
   	 width: 74.99%;
   }
   .col-sm-10 {
   	 width: 83.33%;
   }
   .col-sm-11 {
   	 width: 91.66%;
   }
   .col-sm-12 {
   	 width: 100%;
   }
}

</style>
</head>
<body>
	<h2>Our Menu</h2>
	<div class="row">
	<div class="col-lg-4 col-md-6 col-sm-12">
		<div class="fix"><p class="ch">Chicken</p><br><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div></div>
	<div class="col-lg-4 col-md-6 col-sm-12">
		<div class="fix"><p class="be">Beef</p><br><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div></div>
	<div class="col-lg-4 col-md-6 col-sm-12">
		<div class="fix"><p class="su">Sushi</p><br><br>Lorem ipsum dolor sit amet,consectetur adipisicing elit,sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</div></div>
    
</div>
</body>
</html>
