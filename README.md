file:///Users/darinaadilkhanova/Desktop/PROJ%202/mainpage.html

<!DOCTYPE html>
<html>
<head>
	<title>Gaudi Portfolio Website</title>
	<meta charset="utf-8">
	<link href="stylesheet/mainpage.css" rel="stylesheet" type="text/css"/>

	


</head>

<body>


<div id="container">
  <div id="container2">
  	 <div class="box one"><div><h1>GAUDI</h1></div></div>
    <div class="box two"><div><img src="1.jpg" class="center"></div></div>
    <div class="box three"><div><img src="2.jpg" class="center"></div></div>
    <div class="box four"><div><img src="3.jpg" class="center"></div></div>
    <div class="box five"><div><img src="4.jpg" class="center"></div></div>
    <div class="box six"><div><img src="5.jpg" class="center"></div></div>
    <div class="box seven"><div><img src="6.jpg" class="center"></div></div>
    <div class="box eight"><div><img src="7.jpg" class="center"></div></div>
    <div class="box nine"><div><img src="8.jpg" class="center"></div></div>

    <div class="relative">Building Exterior</div>

  </div>
</div>



</body>
</html>




body {
  margin:0;
  padding:0;
  font-family:Didot;
}



h1{
  color:black;
}

h2{
  color:black;
  font-size: 100px;
  font-family: Didot;
  font-weight: bold;
  position: absolute;
}



#container .box {
  width:100vw;
  height:100vh;
  display:inline-block;
  position:relative;
}
#container .box > div {
  width:100px;
  height:100px;
  font-size:110px;
  color:#FFF;
  position:absolute;
  top:50%;
  left:50%;
   margin:-50px 0 0 -50px;
  transform: translateX(-370%) translateY(-180%);
  line-height:.7;
  font-weight:bold;
}
#container {
  overflow-y:scroll;
  overflow-x:hidden;
  transform: rotate(270deg) translateX(-100%);
  transform-origin: top left;
  background-color:#999;
  position:absolute;
  width:100vh;
  height:100vw;
}
#container2 {
  transform: rotate(90deg) translateY(-100vh);
  transform-origin: top left;
  white-space:nowrap;
  font-size:0;
}


img {
  height: auto;
  width:700px;
}



