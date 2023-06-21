# CRMFinal
Redisign of CRM

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <script src="https://kit.fontawesome.com/dd8c49730d.js" crossorigin="anonymous"></script>
  <title>INDEX CRM</title>
  <link rel="stylesheet" href="inicioncrm.css">
</head>

<?php
                                    /*CRM System*/
                     /* Developed by Oswaldo Jesús Marín Pagés*/
/* Como Requisito para la obtención del Grado de Licenciado en Ciencias de la Computación e Informática*/
/* Universidad Nueva Esparta. Sede: Los Naranjos del Cafetal. Municipio El Hatillo. Junio 2017*/
?>

<body>

  <div class="container" id="container">
    
    <div class="overlay-container">
      <div class="overlay">
        
        <div class="overlay-panel overlay-right">
          <h1>CRM SYSTEM</h1>
          <p>Please sign up to connect with To CRM SYSTEM</p>
          <button class="ghost" id="signUp"><a href="menuncrm.html" style="color: white;">Sign Up</button>
		  
    
        </div>
		
      </div>
	  
    </div>

    <script src="main1.js"></script>
	
</body>

</html>

CSS:

@import url("https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  color: #ccc;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-image: url(img/laptop.jpg);
  background-size: cover;
}

h1 {
  font-size: 30px;
  font-weight: 800;
  font-family: "roboto", sans-serif;
}

span {
  font-size: 15px;
  color: white;
  font-family: "Roboto Condensed", sans-serif;
}

p {
  font-size: 14px;
  font-weight: bold;
  line-height: 20px;
  letter-spacing: 0.5px;
  margin: 20px 0 30px;
  font-family: "Roboto", sans-serif;
}

.container {
  position: absolute;
  box-shadow: 2.8px 2.8px 2.2px #05050594, 8px 9px 9px #00000017, 9px 10px 10px #00000017, 7px 9px 11px #00000017, 7px 7px 2px #00000017, 6px 11px 13px #000; 
  overflow: hidden;
  min-height: 480px;
  width: 768px;
  max-width: 100%;
  opacity: 1;
}

button {	
  color: white;
  font-size: 15px;
  font-weight: bold;
  padding: 12px 35px;
  margin-top: 15px;
  border: 5px solid #ff4b2b;
  border-radius: 25px;
  text-transform: uppercase;
  transition: transform 80ms ease-in;
}

button:active {
  transform: scale(0.95);
}

button:focus {
  outline: none;
}

.ghost {
  background: transparent;
  border-color: #ff4b2b;
  background-color: #64a6e1;
}

.overlay-container {
  position: absolute;
  top: 0;
  left: 35%;
  width: 35%;
  height: 100%; 
}

.overlay {
  background: transparent;
  background: linear-gradient(to right, #ff4b2b, #ff416c) no repeat 0 0 / cover;
  color: #fff;
  position: absolute;
  left: -100%;
  height: 100%;
  width: 200%;
  transform: translateX(0);
  transition: transform 0.6s ease-in-out;
}

.overlay-panel {
  position: absolute;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 40px;
  height: 100%;
  width: 50%;
  text-align: center;
  transform: translateX(0);
  transition: transform 0.6s ease-in-out;
}

.overlay-right {
  right: 0;
  transform: translateX(0);
}

.overlay-left {
  transform: translateX(-20%);
}

Web Page 2:

HTML:

<!DOCTYPE html>   
  <html lang="en">   
  <head>   
   <meta charset="UTF-8" />   
   <meta http-equiv="X-UA-Compatible" content="IE=edge" />   
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />   
   <title> Flex Hover Slider</title>   
   <link rel="stylesheet" href="menuncrm.css">  
  </head>   
  <body>   
   <div class="flex-container">  
     <div class="spinner"><p>  
       <div class="cube1"></div>  
       <div class="cube2"></div>  
       Loading...  
       </p>  
     </div>  
	 
<?php
                                    /*CRM System*/
                     /* Developed by Oswaldo Jesús Marín Pagés*/
                    /*Enlaces de la diferentes areas del CRM*/

?>

     <div class="flex-slide home">  
       <div class="flex-title flex-title-home">Centros</div>  
       <div class="flex-about flex-about-home"><p>Click here to navigate to the home section of the Centros</p></div>  
     </div>  
     <div class="flex-slide home">  
       <div class="flex-title flex-title-home">Formacion</div>  
       <div class="flex-about flex-about-home"><p>Click here to navigate to the home section of the Formacion</p></div>  
     </div>  
     <div class="flex-slide home">  
       <div class="flex-title flex-title-home">Bolsa de Empleo</div>  
       <div class="flex-about flex-about-home"><p>Click here to navigate to the home section of the Bolsa de Empleo</p></div>  
     </div>  
     <div class="flex-slide home">  
       <div class="flex-title flex-title-home">Tecnologia</div>  
       <div class="flex-about flex-about-home"><p>Click here to navigate to the home section of the Tecnologia</p></div>  
     </div>
     
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>  
   <script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/769286/jquery.waitforimages.min.js"></script>
   <script src="menu11.js"></script>  
  </body>   
  </html>   

  CSS:

  @import url('https://fonts.googleapis.com/css?family=Raleway');  
$defaultSeconds: 3s;
body {  
      margin: 0;  
      padding: 0;  
      font-family: 'Robato', sans-serif;  
 }  
 
 .flex-container {  
      position: absolute;  
      height: 100vh;  
      width: 100%;  
      display: -webkit-flex; /* Safari */  
      display: flex;  
      overflow: hidden;  
      @media screen and (max-width: 768px) {  
           flex-direction: column;  
      }  
 }  
 
  .flex-title {  
      color: #f1f1f1;  
      position: relative;  
      font-size: 6vw;  
      margin: auto;  
      text-align: center;  
      transform: rotate(90deg);  
      top: 15%;  
      -webkit-transition: all 500ms ease;  
      -moz-transition: all 500ms ease;  
      -ms-transition: all 500ms ease;  
      -o-transition: all 500ms ease;  
      transition: all 500ms ease;  
      @media screen and (max-width: 768px) {  
           transform: rotate(0deg) !important;  
      }  
 }  

 .flex-about {  
      opacity: 0;  
      color: #ffffff;  
      position: relative;  
      width: 70%;  
      font-size: 2vw;  
      padding: 5%;  
      top: 20%;  
      border: 2px solid #f1f1f1;  
      border-radius: 10px;  
      line-height: 1.3;  
      margin: auto;  
      text-align: left;  
      transform: rotate(0deg);  
      -webkit-transition: all 500ms ease;  
      -moz-transition: all 500ms ease;  
      -ms-transition: all 500ms ease;  
      -o-transition: all 500ms ease;  
      transition: all 500ms ease;  
      @media screen and (max-width: 768px) {  
           padding: 0%;  
           border: 0px solid #f1f1f1;  
      }  
 } 

.flex-slide {  
      -webkit-flex: 1; /* Safari 6.1+ */  
      -ms-flex: 1; /* IE 10 */    
      flex: 1;  
      cursor: pointer;  
      -webkit-transition: all 500ms ease;  
      -moz-transition: all 500ms ease;  
      -ms-transition: all 500ms ease;  
      -o-transition: all 500ms ease;  
      transition: all 500ms ease;  
      @media screen and (max-width: 768px) {  
           overflow: auto;  
           overflow-x: hidden;  
      }  
 }  

.flex-slide p {  
      @media screen and (max-width: 768px) {  
           font-size: 2em;  
      }  
 }  

 .flex-slide ul li {  
      @media screen and (max-width: 768px) {  
           font-size: 2em;  
      }  
 }   
 .flex-slide:hover {  
      -webkit-flex-grow: 3;  
      flex-grow: 3;  
 }  

.home {  
      height: 100vh;  
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(img/laptop.jpg);  
      background-size: cover;  
      background-position: center center;  
      background-attachment: fixed;  
      @media screen and (min-width: 768px) {  
           animation: aboutFlexSlide $defaultSeconds 1;  
           animation-delay: 0s;  
      }  
 }   

