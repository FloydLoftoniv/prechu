# prechu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
* {
    box-sizing: border-box;
    
}

body {
    position: relative;
  
    background: white;
    font-family: sans-serif;
    line-height: 1.5;
 width: auto;
}

header{
    
    padding-left: 90px;
    padding-right: 90px;
        font-weight: 900;
        position: relative;
}
.logo{
   display: inline; 
 
    
}
.nav{
    margin-top: 0px;
    float: right;
}

.nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

.nav li {
    display: inline;
    padding-left: 30px;
    padding-right: 30px;
    text-transform: uppercase;
    font-weight: 900;
}
.hero_img{
    width: 100%;
}
.middle{
 
display: flex;
margin-left: 20px;
    margin-right: 20px;
    text-align: center;
    justify-content: center;
}


.middle li {
    position: absolute;
    float: right;
    justify-content: space-evenly;
    
}

 .contray{
    margin-left: auto;
    margin-right: auto;
    align-content:space-between;
padding: 30px;
}

footer{
position: relative;
    margin-left: 40px;
    margin-right: 40px;
    padding: 10px;
 text-size-adjust: 40px;
display: flex;
 }
 
 .bullet{
     position: absolute;
    justify-content: space-around;
    left: 20px;
    font-size: 30px;
 }
 .bullet img{
     width: 90%;
     height: 90%;

 }

.bullet2{
    position: absolute;
    justify-content: space-around;
     right: 0px;
     line-height: 50px;
    
 }
 .bullet2 h2{
    font-size: 40px;
    right: 10px;
 }
 .bullet2 ul{

      list-style: none;
 }

</style>

<link rel="stylesheet" href="C:\Users\floyd\Desktop\Vswork\Gradedwork\prechu\prechu.css">

<body>
 <header> 
     <div class="logo">
    <h1><img src="file:///C:/Users/floyd/Desktop/Vswork/media/mark.png" alt="circle"> Prechu</h1> 
 </div>
 <ul class="nav" >
     <li>Home</li>
     <li>Product</li>
     <li>Service</li>
     <li>Contact</li>
 </ul>
 
</header>
<img class="hero_img" src="file:///C:/Users/floyd/Desktop/Vswork/media/download.png" alt="phone">
<div class="middle">
  <div class="contary">
    <img src="file:///C:/Users/floyd/Desktop/Vswork/media/download%20(1).png" alt="pen">
    <h2>Contray to popular</h2>
    <p>Lorem is not simlpy random text it has roots in a piece</p>
  </div>
  <div class="contary">
    <img src="file:///C:/Users/floyd/Desktop/Vswork/media/download%20(2).png" alt="Tv">
    <h2>Contray to popular</h2>
    <p>Lorem is not simlpy random text it has roots in a piece</p>
   </div>
   <div class="contary">
    <img src="file:///C:/Users/floyd/Desktop/Vswork/media/download%20(3).png" alt="basket">
    <h2>Contray to popular</h2>
    <p>Lorem is not simlpy random text it has roots in a piece</p>
 </div>
</div>

<footer>
 <div class="bullet">
                       <h2>The Shopping Cart</h2>
    <img src="file:///C:/Users/floyd/Desktop/Vswork/media/download%20(4).png" alt="cart">
</div>
    <div class="bullet2">
    <h2>Some Bullet Text Here</h2>
    <ul>
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae!</li>
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
        <li>Lorem, ipsum dolor sit amet consectetur adipisicing.</li>
       <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora, minima!</li>
        <li>Lorem ipsum dolor sit amet consectetur.</li>
        <li>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</li>
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni sint libero ad perferendis?</li>
    </ul>
 </div>
</footer>



</body>
</html>
