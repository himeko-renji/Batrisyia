<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nur Batrisyia Resume</title>

<style>
body {
  margin: 0;  /* remove white edges */
  padding: 0;
  height: 100vh; /* make sure it fills the full view height */
  background-image: url(gnf.jpeg);  /* change to your file */
  background-size: cover;      /* fills entire page */
  background-repeat: no-repeat;/* stops repeating */
  background-position: center; /* centers the image */
  background-attachment: fixed;/* optional: keeps image fixed when scrolling */
  padding: 10px;
  align-items: left;
  box-sizing: border-box;
  height: 100%;
  width: 100%;
}

.body:hover{
  color:#ffffff;
}

.header {
  display: flex;
  background-color: #000000;
  color:#ffffff;
  align-items: center;
  padding: 15px 30px;
  border-bottom: 5px solid #FFD700;
  justify-content: space-between;
  top: 0;
  z-index: 10;
  border-radius: 20px;
}

.container{
  display: flex;          /* places items side by side */
  align-items: center;    /* vertically center text with the circle */
  gap: 10px;              /* space between circle and text */
    
}

.circle{
  width: 65px;
  height: 65px;
  border-radius: 50%;
  background-image: url(icon.jpeg);
  background-size: cover;
  background-position: center;
}







/* Nav Links */
.nav-links {
  list-style: none;
  display: flex;
  gap: 25px;
}

.nav-links li a {
  text-align: center;
  font-family:"times new roman";
  text-decoration: none;
  color: #ffffff;
  font-size: 21px;
  transition: 0.3s;
}

.nav-links li a:hover {
  color: #fff;
  text-shadow: 0 0 10px #ffffff;
}





/* form */
fieldset {
  border-left: 5px solid #FFD700;
  border-radius: 20px;
  padding: 15px 25px;
  background-color: #000000bb; /* last two digits (75) = transparency */
  color: #ffffff;
}

legend {
  font-size:55px;
  color: #f7f6f2;
  text-shadow: 0 0 15px #FFD700;
  text-align: left;
  font-weight: bold;
}

p {
  font-size: 23px;
  font-weight: bold;
  justify-content:flex-end;
  text-align: start;
}



.footer {
  background-color: #000000;
  color: #fbf9fc;
  text-align: center;
  padding: 15px 0;
  font-size: 18px;
  justify-content:bottom;
  border-radius: 20px;
  margin-top: 10px;
  padding: 15px;
  border-top: 5px solid #FFD700;
}



</style>
</head>


<body>
<div class="header">
  <div class="container">
  <div class="circle"></div>
  <h2>BATRISYIA</h2>
  </div>
<nav>
  <ul class="nav-links">
    <li><a href="background.html" target="_blank">&#128100; ABOUT ME</a></li>
    <li><a href="family.html" target="_blank">&#129293; FAMILY</a></li>
    <li><a href="educational.html" target="_blank">&#128175; EDUCATION</a></li>
    <li><a href="hobby.html" target="_blank">&#127918; HOBBY</a></li>
    <li><a href="socmed.html" target="_blank">&#128293; SOCIAL MEDIA</a></li>
  </ul>
</nav>
</div>






<div class="form">
  <fieldset>
  <legend>Hey There!</legend>
  <p>My Name is Nur Batrisyia binti Ahmad Tarmizi and I am a passionate and dedicate Website Designer.</p>
  <p>I am currently studying in UiTM, Segamat, Johor in Diploma Information Management</p>
  <p>My Hometown is at Shah Alam, and currently live in Johor.</p>
 <p>As a first child of two, I carried a responsibility to be a good daugther and student</p>
 <p>Also, As an older sister, I have to be a good role model for my brother.</p>
 <p>I started as an Information Management student, then realized my love for Website Design as my career path.</p>
 <p>I believed in my skills and am confident that I can contribute positively to the team.</p>
</div></fieldset>


  
<div class="footer">
  
  <b>Copyright © 2025 Nur Batrisyia binti Ahmad Tarmizi</b>
  

</div>




</body>
</html>
