
<!DOCTYPE html>
<HTML>
 <HEAD>
 
  <link href='http://fonts.googleapis.com/css?family=Shadows+Into+Light' rel='stylesheet' type='text/css'>
<style>
body {
	background-image: url(http://3.bp.blogspot.com/-GU9R4JHlLEY/TZIV29hjOzI/AAAAAAAAAC4/HpltvSmljLs/s1600/Black_Eyes.jpg);
	background-size: 1300px 950px;
	background-position: 50% 400%;
}

#ball {
    position            : absolute;
    display             : block;
    top                 : 180px;
    left                : 550px;
    width               : 120px;
    height              : 120px;
    background-color    : rgba(255,255,255,0.9);
    background-image: url(http://area.autodesk.com/userdata/image/stencil/6/68g71-5fnhm-qw81n-65z8b.jpg);
    
    border-radius       : 50%;
    box-shadow          : inset 0 0 70px #fff;
    cursor: pointer;
}

small {
    position            : relative;
    display             : block;
    width               : 50px;
    height              : 50px;
    top                 : 12px;
    left                : 12px;
    background-color    : black;
    border-radius       : 50%;
    box-shadow          : 0 0 0 2px #000,
    						inset 0 0 30px #000;
    background-image: url(http://www.zeroterminal.com/uploads/posts/2010-08/1281834954_iris-texture-5.png);
    background-size: cover;
    
}
#ball2 {
    position            : absolute;
    display             : block;
    top                 : 180px;
    left                : 900px;
    width               : 120px;
    height              : 120px;
    background-color    : rgba(255,255,255,0.9);
    border-radius       : 50%;
    background-image: url(http://area.autodesk.com/userdata/image/stencil/6/68g71-5fnhm-qw81n-65z8b.jpg);
    box-shadow          : 
                          inset 0 0 70px #fff;
   	cursor: pointer;
}
 h1 {
 	font-family: 'Shadows Into Light';
 	color: black;
 	font-size: 3em;
 	font-style: bold;
 	position: fixed;
 	z-index: 10;
 	margin-top: -650px;
 	margin-left: 650px;

 }
 h2 {
 	 font-family: 'Shadows Into Light';
 	color: white;
 	font-size: 1.5em;
 	font-style: bold;
 	position: fixed;
 	z-index: 10;
 	margin-top: -40px;
 	margin-left: 10px;
 }
h3 {
	 	font-family: 'Shadows Into Light';
 	color: white;
 	font-size: 1.5em;
 	font-style: bold;
 	position: fixed;
 	z-index: 10;
 	margin-top: -40px;
 	margin-left: 1100px;
}


.floor {
	width				: 100%;
	height				: 200px;
	background-color 	: rgba(210,69,67,1);
	position 			: relative;
	margin-top			: 700px;
	box-shadow 			: inset 0 0 300px #000;
	background-image: url(http://www.wildtextures.com/wp-content/uploads/2011/10/wildtextures-old-wood-original-file.jpg)
}

#ball.animate {
        -webkit-animation-name: "jump";
        -webkit-animation-duration: 3.0s;
        -webkit-animation-iteration-count: infinite;
        //animation-iteration-count: infinite;
        -webkit-animation-timing-function:linear;
}

@-webkit-keyframes jump {
    0% {
        top:150px;
        left: 500px;
        height: 120px;
        width: 120px;
        }
    2%{
        height: 200px;
        width: 200px;
    }
    3%{
        top: 80px;
    }
    6%{
        top:170px;
        height: 140px;
        width: 110px;
    }
    11%{
        height: 130px;
        width: 112px;
    }
    12% {
        top: 610px;
        height: 100px;
        width: 140px;
    }
    13%{
        top:600px;
        height: 105px;
        width: 130px;
    }
    17%{
        height: 125px;
        width: 115px;
    }
    20%{
        top: 400px;
        height: 108px;
        width: 122px;
    }
    24%{
        height: 125px;
        width: 115px;
    }
    29% {
        top: 605px;
        height: 100px;
        width: 130px;
    }
    31% {
        top:600px;
        height: 100px;
        width: 130px;
    }
    33%{
        height: 122px;
        width: 118px;
    }
    36% {
        top: 550px;
        height: 108px;
        width: 122px;   
    }

    39% {
        top: 590px;
        height: 110px;
        width: 125px;
    }
    44% {
        top: 590px;
        height: 110px;
        width: 125px;
    }
    46%{
        top: 570px;
        height: 115px;
        width: 122px;
    }
    48%{
        top: 580px;
    }
    75% {
        top: 580px;
    }
    100% {
        top:580px;
        left: -100px;
    }
}
#ballilla.animating {
        -webkit-animation-name: "jumping";
        -webkit-animation-duration: 3.0s;
        -webkit-animation-iteration-count: infinite;
        //animation-iteration-count: infinite;
        -webkit-animation-timing-function:linear;
}

@-webkit-keyframes jumping {
    0% {
        top:10px;
        
    }
    3%{
        top: 40px;
    }
    6%{
        top:20px;
       
    }

    11%{
       
    }
    12% {
        top: 0px;
       
    }
    13%{
        top: 60px;
        
    }
    17%{
        
    }
    20%{
        top: 20px;
     
    }
    24%{
     
    }
    29% {
        top: 60px;
   
    }
    31% {
        top:60px;
 
    }
    33%{


    }
    36% {
        top: 30px;
    
   
    }

    39% {
        top: 60px;

    }
    44% {
        top: 70px;
   

    }
    46%{
        top: 60px;
        
    }
    48%{
        top: 60px;
        left: 30px;
    }
    75% {
        top: 60px;
        left: 60px;
    }
    90%{
        left: 70px;
    }
    100% {
        top:20px;
        left: 60px;
    }
}

#ball2.animate2 {
        -webkit-animation-name: "jump2";
        -webkit-animation-duration: 3.0s;
        -webkit-animation-iteration-count: infinite;
        //animation-iteration-count: infinite;
        -webkit-animation-timing-function:linear;
}

@-webkit-keyframes jump2 {
    0% {
        top:150px;
        left: 950px;

    }
    6% {
        top:150px;
        left: 950px;
        height: 120px;
        width: 120px;
    }
    8%{
        height: 200px;
        width: 200px;
    }
    9%{
        top: 80px;
    }
    12%{
        top:170px;
        height: 140px;
        width: 110px;
    }
    17%{
        height: 130px;
        width: 112px;
    }
    18% {
        top: 610px;
        height: 100px;
        width: 140px;
    }
    19%{
        top:600px;
        height: 105px;
        width: 130px;
    }
    23%{
        height: 125px;
        width: 115px;
    }
    26%{
        top: 400px;
        height: 108px;
        width: 122px;
    }
    30%{
        height: 125px;
        width: 115px;
    }
    35% {
        top: 605px;
        height: 100px;
        width: 130px;
    }
    37% {
        top:600px;
        height: 100px;
        width: 130px;
    }
    39%{
        height: 122px;
        width: 118px;
    }
    42% {
        top: 550px;
        height: 108px;
        width: 122px;   
    }

    45% {
        top: 590px;
        height: 110px;
        width: 125px;
    }
    49% {
        top: 590px;
        height: 110px;
        width: 125px;
    }
    52%{
        top: 570px;
        height: 115px;
        width: 122px;
    }
    54%{
        top: 580px;
    }
    81% {
        top: 580px;
    }
    100% {
        top:580px;
        left: 1800px;
    }
}
#ballilla2.animating2 {
        -webkit-animation-name: "jumping2";
        -webkit-animation-duration: 3.0s;
        -webkit-animation-iteration-count: infinite;
        //animation-iteration-count: infinite;
        -webkit-animation-timing-function:linear;
}

@-webkit-keyframes jumping2 {
    6% {
        top:10px;
        
    }
    9%{
        top: 40px;
    }
    12%{
        top:20px;
      
    }
    17%{
       
    }
    18% {
        top: 0px;
       
    }
    19%{
        top: 70px;
        
    }
    23%{
        
    }
    26%{
        top: 5px;
     
    }
    30%{
     
    }
    35% {
        top: 60px;
   
    }
    37% {
        top:60px;
 
    }
    39%{


    }
    42% {
        top: 20px;
    
   
    }

    45% {
        top: 60px;

    }
    49% {
        top: 70px;
   

    }
    52%{
        top: 60px;
        
    }
    54%{
        top: 60px;
        left: 30px;
    }
    81% {
        top: 60px;
        left: 10px;
    }
    90%{
        left: 0px;
    }
    100% {
        top:20px;
        left: 10px;
    }
}
</style>

 </HEAD>
 <BODY>
 <h1> EL PETA OJOS </h1>
 <h2> Haz click en uno de los globos oculares... </h2>
 <h3> ...para generar una fuente infinita de ojos </h3>
 <span>
   <div id="ball">
    
          <small  id="ballilla"></small> 
    
   </div> 
   <div id="ball2">
    
          <small id="ballilla2"></small>
    
   </div> 
 </span>
   <div class="floor"> 
   </div>
  <script src="jquery-2.1.1.js"></script>
  <script> 
   $("#ball").on("click", function(event){
        $('#ball').addClass('animate');
        $('#ballilla').addClass('animating');
   });
   
       $("#ball2").on("click", function(event){
        $('#ball2').addClass('animate2');
        $('#ballilla2').addClass('animating2');
   });
  </script>
 </BODY>
</HTML>
