# Cars
<!DOCTYPE html>
<html>
<head>
<style>

body {
    background-image: url("black-wallpaper-13.jpg");
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
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}
</style>



<ul>
  <li><a class="active" href="#home">Home</a></li>

 <li><a href="#news">News</a></li>


 <li class="dropdown">
    <a href="#" class="dropbtn">Cars</a>
    <div class="dropdown-content">
      <a href="#">Make</a>
      <a href="#">Year</a>
	  <li style="float:right"><a class="active" href="#about">Log In</a></li>
    </div>
  </li>
</ul>

<style>
div.img {
    border: 1px solid #ccc;
}

div.img:hover {
    border: 1px solid #777;
}

div.img img {
    width: 100%;
    height: auto;
}

div.desc {
    padding: 15px;
    text-align: center;
}

* {
    box-sizing: border-box;
}

.responsive {
    padding: 0 6px;
    float: left;
    width: 24.99999%;
}

@media only screen and (max-width: 700px){
    .responsive {
        width: 49.99999%;
        margin: 6px 0;
    }
}

@media only screen and (max-width: 500px){
    .responsive {
        width: 100%;
    }
}

.clearfix:after {
    content: "";
    display: table;
    clear: both;
}
</style>


<style>
div.img {
    margin: 5px;
    border: 1px solid #ccc;
    float: left;
    width: 180px;
}

div.img:hover {
    border: 1px solid #777;
}

div.img img {
    width: 100%;
    height: auto;
}

div.desc {
    padding: 15px;
    text-align: center;
}
</style>
</head>
<body>

<div class="img">
  <a target="_blank" href="img_fjords.jpg">
    <img src="Acura.jpg" alt="Acura" width="300" height="200">
  </a>
 <div class="desc"><p style="color:red;">Acura</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_forest.jpg">
    <img src="alfa.jpg" alt="alfa Romeo" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Alfa Romeo</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_lights.jpg">
    <img src="Aston.jpg" alt="aston" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Aston Martin</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_mountains.jpg">
    <img src="audi.jpg" alt="audi" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Audi</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_fjords.jpg">
    <img src="bentley.jpg" alt="Bentley" width="300" height="200">
  </a>
  <div class="desc"><p style="color:red;">Bently</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_forest.jpg">
    <img src="BMW.jpg" alt="BMW" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">BMW</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_lights.jpg">
    <img src="bugatti.jpg" alt="bugatti" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Bugatti</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_mountains.jpg">
    <img src="Buick.jpg" alt="buick" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Buick</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_fjords.jpg">
    <img src="cadillac.jpg" alt="caddilac" width="300" height="200">
  </a>
  <div class="desc"><p style="color:red;">Cadillac</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_forest.jpg">
    <img src="Chevy.jpg" alt="chevy" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Chevrolet</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_lights.jpg">
    <img src="Chrysler.jpg" alt="Chrysler" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Chrysler</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_mountains.jpg">
    <img src="citroGen.jpg" alt="citroen" width="600" height="400">
  </a>
<div class="desc"><p style="color:red;">Citroen</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_fjords.jpg">
    <img src="Dodge.jpg" alt="dodge" width="300" height="200">
  </a>
  <div class="desc"><p style="color:red;">Dodge</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_ferrari.jpg">
    <img src="Ferrari.jpg" alt="Ferrari" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Ferrari</p></div>
</div>

<div class="img">
  <a target="_blank" href="img_fiat.jpg">
    <img src="fiat.jpg" alt="fiat" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Fiat</p></div>
</div>

<div class="img">
  <a target="_blank" href="ford.jpg">
    <img src="ford.jpg" alt="ford" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Ford</p></div>
</div>

<div class="img">
  <a target="_blank" href="gmc.jpg">
    <img src="gmc.jpg" alt="ford" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">GMC</p></div>
</div>

<div class="img">
  <a target="_blank" href="honda.jpg">
    <img src="honda.jpg" alt="honda" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Honda</p></div>
</div>

<div class="img">
  <a target="_blank" href="hyundai.jpg">
    <img src="hyundai.jpg" alt="hyundai" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Hyundai</p></div>
</div>

<div class="img">
  <a target="_blank" href="infiniti.jpg">
    <img src="infiniti.jpg" alt="infiniti" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Infiniti</p></div>
</div>

<div class="img">
  <a target="_blank" href="jaguar.jpg">
    <img src="jag.jpg" alt="jaguar" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Jaguar</p></div>
</div>

<div class="img">
  <a target="_blank" href="jeep.jpg">
    <img src="jeep.jpg" alt="jeep" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Jeep</p></div>
</div>

<div class="img">
  <a target="_blank" href="kia.jpg">
    <img src="kia.jpg" alt="kia" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Kia</p></div>
</div>

<div class="img">
  <a target="_blank" href="koen.jpg">
    <img src="koenigsegg.jpg" alt="koenigsegg" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Koenigsegg</p></div>
</div>

<div class="img">
  <a target="_blank" href="lambo.jpg">
    <img src="lamborghini.jpg" alt="lambo" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Lamborghini</p></div>
</div>

<div class="img">
  <a target="_blank" href="landrover.jpg">
    <img src="landrover.jpg" alt="landrover" width="600" height="400">
  </a>
  <div class="desc"><p style="color:red;">Land-Rover</p></div>
</div>


</body>
</html>
