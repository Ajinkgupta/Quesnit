Index.html

```
<!DOCTYPE html>
<html lang="en">
 <head>
 <meta charset="UTF-8" />
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <link rel="stylesheet" href="assets/style.css" />
 <title>MyCollege</title>
 </head>
 <body>
 <nav class="navbar">
 <!-- LOGO -->
 <div class="logo">My College</div>
 <!-- NAVIGATION MENU -->
 <ul class="nav-links">
 <!-- USING CHECKBOX HACK -->
 <input type="checkbox" id="checkbox_toggle" />
 <label for="checkbox_toggle" class="hamburger">&#9776;</label>
 <!-- NAVIGATION MENUS -->
 <div class="menu">
 <li><a href="">Home</a></li>
 <li><a href="#">About</a></li>
 <li class="facilities">
 <a href="#">Facilities</a>
 <!-- DROPDOWN MENU -->
 <ul class="dropdown">
 <li><a href="#library">Library</a></li>
 <li><a href="#lab">Laboratory</a></li>
 <li><a href="#l3">Auditoriam</a></li>
 <li><a href="#l4">Gymkhana</a></li>
 
 </ul>
 </li>
 <li><a href="#">Policy</a></li>
 <li><a href="#">Contact</a></li>
 </div>
 </ul>
 </nav>

 <div class="intro">
 <img src="https://www.kadencewp.com/wp-content/uploads/2020/10/alogo-2.png" width="200px" alt="">
 <h1>My College</h1>
 <p>We create leaders</p>
 </div> 

 <div class="row">

 <div class="main">
 

 
<style> 
 .mySlides {display: none}
 .mySlides img {vertical-align: middle;}
 
 /* Slideshow container */
 .slideshow-container {
 max-width: 1000px;
 position: relative;
 margin: auto;
 }
 
 /* Next & previous buttons */
 .prev, .next {
 cursor: pointer;
 position: absolute;
 top: 50%;
 width: auto;
 padding: 16px;
 margin-top: -22px;
 color: white;
 font-weight: bold;
 font-size: 18px;
 transition: 0.6s ease;
 border-radius: 0 3px 3px 0;
 user-select: none;
 }
 
 /* Position the "next button" to the right */
 .next {
 right: 0;
 border-radius: 3px 0 0 3px;
 }
 
 /* On hover, add a black background color with a little bit see-through */
 .prev:hover, .next:hover {
 background-color: rgba(0,0,0,0.8);
 }
 
 /* Caption text */
 .text {
 color: #f2f2f2;
 font-size: 15px;
 padding: 8px 12px;
 position: absolute;
 bottom: 8px;
 width: 100%;
 text-align: center;
 }
 
 /* Number text (1/3 etc) */
 .numbertext {
 color: #f2f2f2;
 font-size: 12px;
 padding: 8px 12px;
 position: absolute;
 top: 0;
 }
 
 /* The dots/bullets/indicators */
 .dot {
 cursor: pointer;
 height: 15px;
 width: 15px;
 margin: 0 2px;
 background-color: #bbb;
 border-radius: 50%;
 display: inline-block;
 transition: background-color 0.6s ease;
 }
 
 .active, .dot:hover {
 background-color: #717171;
 }
 
 /* Fading animation */
 .fade {
 animation-name: fade;
 animation-duration: 1.5s;
 }
 
 @keyframes fade {
 from {opacity: .4} 
 to {opacity: 1}
 }
 
 /* On smaller screens, decrease text size */
 @media only screen and (max-width: 300px) {
 .prev, .next,.text {font-size: 11px}
 }
 </style>
 </head>
 <body>
 
 <div class="slideshow-container">
 
 <div class="mySlides fade">
 <div class="numbertext">1 / 3</div>
 <img src="https://via.placeholder.com/1000x400" style="width:100%">
 <div class="text">Caption Text</div>
 </div>
 
 <div class="mySlides fade">
 <div class="numbertext">2 / 3</div>
 <img src="https://via.placeholder.com/1000x400" style="width:100%">
 <div class="text">Caption Two</div>
 </div>
 
 <div class="mySlides fade">
 <div class="numbertext">3 / 3</div>
 <img src="https://via.placeholder.com/1000x400" style="width:100%">
 <div class="text">Caption Three</div>
 </div>
 
 <a class="prev" onclick="plusSlides(-1)">❮</a>
 <a class="next" onclick="plusSlides(1)">❯</a>
 
 </div>
 <br>
 
 <div style="text-align:center">
 <span class="dot" onclick="currentSlide(1)"></span> 
 <span class="dot" onclick="currentSlide(2)"></span> 
 <span class="dot" onclick="currentSlide(3)"></span> 
 </div>
 
 <script>
 let slideIndex = 1;
 showSlides(slideIndex);
 
 function plusSlides(n) {
 showSlides(slideIndex += n);
 }
 
 function currentSlide(n) {
 showSlides(slideIndex = n);
 }
 
 function showSlides(n) {
 let i;
 let slides = document.getElementsByClassName("mySlides");
 let dots = document.getElementsByClassName("dot");
 if (n > slides.length) {slideIndex = 1} 
 if (n < 1) {slideIndex = slides.length}
 for (i = 0; i < slides.length; i++) {
 slides[i].style.display = "none"; 
 }
 for (i = 0; i < dots.length; i++) {
 dots[i].className = dots[i].className.replace(" active", "");
 }
 slides[slideIndex-1].style.display = "block"; 
 dots[slideIndex-1].className += " active";
 }
 </script> 


<div id="Library" class="container">
 <h2>Library</h2>
<p>
 A Library is the soul of any educational institution. The curriculum and teaching methods in Pragati College of Arts & Commerce e require both intensive and extensive use of the materials in the library. Keeping in view its essential role, the library is being constantly enriched by the acquisition of latest books and journals. This helps the library to keep in pace with changing times and to further the advancement of the academic endeavors of the college. 

</p>
<p> 
Objectives of the Library:
To acquire develop, maintain and provide a qualitative and quantitative collection of Books, Periodicals and other instructional material to support the academic program and educational objectives of the college.

To encourage use of variety of resources to help prepare students for success in information and technological age and for lifelong learning.

To collaborate with other libraries through a planned resource sharing programme.
</p>
</div>
<br>
<div id="lab" class="container">
 <h2>Laboratory</h2>

 <p><strong>Computer and Internet :</strong></p>
 
 <p>The college has two spacious computer laboratories equipped with 48 Desktop systems - Lab I - 25 Computers, Lab II - 23 Computers with&nbsp; 1 LCD Projector&nbsp; and 1 Lap top. Our computer labs are well equipped with fully air-conditioned and high-end internet facility with 50 Mbps dedicated leased line. &nbsp;The administrative blocks, academic blocks, library and other buildings of the campus are connected through the Wi-Fi. CCTV cameras have been installed for lab surveillance. Sufficient generator and UPS back up are installed to have the undisturbed teaching and learning process.</p>
 
 <p>We have all the systems and printer are connected in LAN. Extra efforts were taken by the lab assistant to keep everything on hand. Practical&rsquo;s are conducted under the supervision of trained IT and Computer staff.&nbsp;</p>
 
 <p>&nbsp;</p>
 
 <p><strong>&nbsp;</strong><strong>Services</strong></p>
 
 <ul>
 <li>Printouts</li>
 <li>Scanning</li>
 <li>Browsing for project work</li>
 <li>To check &nbsp;Results</li>
 </ul>
 
</div>
<br>
<div class="container">

</div>
<br>

 </div>
 <div class="side">
 <h3>Principal's Message</h3>

 <div class="card">
 <img src="https://cdn-icons-png.flaticon.com/512/1999/1999321.png" alt="Avatar" style="width:100px">
 <div class="container">
 <h4><b>Principal MyCollege</b></h4> 
 <p>The prime objective of MyCollege is to focus majorly on providing a platform to a child so that he learns about his inner potential. The School believes in providing top quality education coupled with holistic growth of a child and aims to create a successful global citizen. In today’s dynamic world when every moment a new innovation in technology is evolved, the School provides ample opportunities to students to innovate and think critically and lead the learning process.</p> 
 </div>
 </div>


 <h3>Contact Form</h3>

 <div class="container">
 <form action="">
 <label for="fname">First Name</label>
 <input type="text" id="fname" name="firstname" placeholder="Your name..">
 
 <label for="lname">Last Name</label>
 <input type="text" id="lname" name="lastname" placeholder="Your last name..">
 
 
 
 <label for="subject">Subject</label>
 <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
 
 <input type="submit" value="Submit">
 </form>
 </div>

 </div>



 </div>




 <div class="footer">
 <center>&copy;2022 Mycollege</center>
 </div>
 </body>
</html>


```
style.css
```
/* UTILITIES */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
   }
   body {
    font-family: cursive;
   }
   a {
    text-decoration: none;
   }
   li {
    list-style: none;
   }
   /* NAVBAR STYLING STARTS */
   .navbar {
    display: flex;
    position: fixed;  
top: 0; 
z-index: 999;
box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  width: 100%; 
    align-items: center;
    justify-content: space-between;
    padding: 5px;
    background-color:rgb(174, 0, 255);
    color:white;
   }
   .nav-links a {
    color: #fff;
   }
   /* LOGO */
   .logo {
    font-size: 32px;
   }
   /* NAVBAR MENU */
   .menu {
    display: flex;
    gap: 1em;
    font-size: 18px;
   }
   .menu li:hover {
    background-color: rgb(174, 0, 255);
    border-radius: 5px;
    transition: 0.3s ease;
   }
   .menu li {
    padding: 5px 14px;
   }
   /* DROPDOWN MENU */
   .facilities {
    position: relative; 
   }
   .dropdown {
    background-color:rgb(174, 0, 255);
    padding: 1em 0;
    position: absolute; /*WITH RESPECT TO PARENT*/
    display: none;
    border-radius: 8px;
    top: 35px;
   }
   .dropdown li + li {
    margin-top: 10px;
   }
   .dropdown li {
    padding: 0.5em 1em;
    width: 8em;
    text-align: center;
   }
   .dropdown li:hover {
    background-color:rgb(174, 0, 255);
   }
   .facilities:hover .dropdown {
    display: block;
   }
   
   
   /*RESPONSIVE NAVBAR MENU STARTS*/
   /* CHECKBOX HACK */
   input[type=checkbox]{
    display: none;
   } 
   /*HAMBURGER MENU*/
   .hamburger {
    display: none;
    font-size: 24px;
    user-select: none;
   }
   /* APPLYING MEDIA QUERIES */
   @media (max-width: 768px) {
   .menu { 
    display:none;
    position: absolute;
    background-color:rgb(174, 0, 255);
    right: 0;
    left: 0;
    text-align: center;
    padding: 16px 0;
   }
   .menu li:hover {
    display: inline-block;
    background-color:rgb(174, 0, 255);
    transition: 0.3s ease;
   }
   .menu li + li {
    margin-top: 12px;
   }
   input[type=checkbox]:checked ~ .menu{
    display: block;
   }
   .hamburger {
    display: block;
   }
   .dropdown {
    left: 50%;
    top: 30px;
    transform: translateX(35%);
   }
   .dropdown li:hover {
    background-color: rgb(174, 0, 255);
   }
   } 
   .footer {
    padding: 20px;
    text-align: center;
    background: rgb(174, 0, 255)
  }
  .row {  
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
  }
   
  .side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
  } 
  .main {   
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color: white;
    padding: 20px;
  }
   
  .fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
  }
  @media screen and (max-width: 700px) {
    .row {   
      flex-direction: column;
    }
  }
  .intro {
    padding: 60px;
    text-align: center;
    background: #1abc9c;
    color: white;
    font-size: 30px;
  }
  .card {
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
     
  }
  
  .card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  
  .container {
    padding: 2px 16px;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
    border-radius:5px ;
  }
  /* Style inputs with type="text", select elements and textareas */
input[type=text], select, textarea {
    width: 100%; /* Full width */
    padding: 12px; /* Some padding */ 
    border: 1px solid #ccc; /* Gray border */
    border-radius: 4px; /* Rounded borders */
    box-sizing: border-box; /* Make sure that padding and width stays in place */
    margin-top: 6px; /* Add a top margin */
    margin-bottom: 16px; /* Bottom margin */
    resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
  }
  
  /* Style the submit button with a specific background color etc */
  input[type=submit] {
    background-color: #04AA6D;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  /* When moving the mouse over the submit button, add a darker green color */
  input[type=submit]:hover {
    background-color: #45a049;
  }
  .side h3{padding:10px ;}
```
