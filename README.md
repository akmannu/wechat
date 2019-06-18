<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css?family=Righteous&display=swap" rel="stylesheet">
    <link rel='stylesheet' href='https://use.fontawesome.com/releases/v5.7.0/css/all.css' integrity='sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ' crossorigin='anonymous'>
     <link href="https://fonts.googleapis.com/css?family=Pacifico|Permanent+Marker&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet"><script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
     <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
      <style>
         #con1{
           padding-left: 40px;
           padding-top: 20px;
           background-color: white;
        }
         .fl{
           float: right;
         }
         .column {
    float: left;
    width: 100%;
    padding-left: 120px;
    padding-top: 70px;
    padding-bottom: 70px;
    padding-right: 70px;
    margin:50px;
    background-color: grey;
      
  }
  #style1{
    width:100px;
    margin-left: 40px;
  }
  #row1:after {
content: "";
display: table;
clear: both;
}
@media screen and (max-width:600px) {
.column {
  width: 100%;
}
}
h3{
  font-family: 'Pacifico', cursive;
font-family: 'Permanent Marker', cursive;
  color: grey;
  font-weight:bolder;
  font-size: 2.5rem;
}

.dropdown-item
{
  color:grey;
}
</style>


  </head>
  <body>
<!title>
  <div class="container-fluid" id="con1">
      <div class="row">
        <div class="col-lg-8">
    <h3>Learner</h3></div>
       <div class="col-lg-4"> <form class="form-inline" action="">
    <input class="form-control mr-lg-2" type="text" placeholder="Search">
    <button class="btn  btn-sm" type="submit"  style="background-color:white;"><i class="fab fa-searchengin" style="font-size:40px;"></i></button>
  </form>
   </div>
  </div>
   <!navigationbar>
 </div class="container-fluid">

<nav class="navbar navbar-expand-lg bg-dark navbar-dark sticky-top">
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
<ul class="navbar-nav">
  <li class="nav-item ">
    <a class="nav-link active" href="#">
      <i class='fas fa-home' style='font-size:20px'></i>
    <b>  HOME</b></a>
  </li>
  <li class="nav-link"><B>HTML</B></LI>
    <li class="nav-link"><B>CSS</B></LI>
      <li class="nav-link"><B>JAVASCRIPT</B></LI>
        <li class="nav-link"><B>SQL</B></LI>
          <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                <B>DATA STRUCTURE</B>
              </a>
              <div class="dropdown-menu bg-dark" style="color:white;">
                <a class="dropdown-item" href="#">Array</a>
                <a class="dropdown-item" href="#">LinkList</a>
                <a class="dropdown-item" href="#">Stack</a>
                  <a class="dropdown-item" href="#">Graph</a>
                    <a class="dropdown-item" href="#">Tree</a>
              </div>
            </li>
  <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle " href="#" id="navbardrop" data-toggle="dropdown">
      <B>PROGRAMMING LANGUAGES</B>
      </a>
      <div class="dropdown-menu bg-dark">
        <a class="dropdown-item" href="#">C</a>
        <a class="dropdown-item" href="#">C++</a>
        <a class="dropdown-item" href="#">Java</a>
          <a class="dropdown-item" href="#">Python</a>
            <a class="dropdown-item" href="#">Javascript</a>
      </div>
    </li>
    <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
        <b>STUDENT</b>
          </a>
          <div class="dropdown-menu bg-dark">
            <a class="dropdown-item" href="#">Internship</a>
            <a class="dropdown-item" href="#">Placement courses</a>
            <a class="dropdown-item" href="#">Project</a>
              <a class="dropdown-item" href="#">Testimonials</a>
                <a class="dropdown-item" href="#">Careers</a>
          </div>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown" href="#"><B>PRACTICE</B></a>
          <div class="dropdown-menu bg-dark">
            <a class="dropdown-item" href="#">Html</a>
            <a class="dropdown-item" href="#">Css</a>
            <a class="dropdown-item" href="#">JavaScript</a>
              <a class="dropdown-item" href="#">SQL</a>
              <a class="dropdown-item" href="#">Data Structure</a>
            <a class="dropdown-item" href="#">Language</a></div></li></ul>
            </nav>
</div>
  <div class="container-fluid">
    <div class="row" id="row1">
  <div class="column">
    <h1>HTML</h1>
    <p>
The language for building web pages.</p>

   <button type="button" class="btn btn-lg" style="background-color:Black; color:white">LEARN HTML</button>
  <button type="button" class="btn btn-lg" style="background-color:Black; color:white">HTML REFERENCE</button>
</div>
  </div>
  <div class="row" id="row1">
  <div class="column">
    <h1>CSS</h1>
    <p>The language for styling web pages.</p>
    <button type="button" class="btn btn-lg" style="background-color:Black; color:white">LEARN CSS</button>
    <button type="button" class="btn btn-lg" style="background-color:Black; color:white">CSS REFERENCE</button>
  </div>
  </div>
  <div class="row" id="row1">
  <div class="column">
    <h1>JavaScript</h1>
    <p>The language for programming web pages.</p>
    <button type="button" class="btn btn-lg" style="background-color:Black; color:white">LEARN JavaScript</button>
    <button type="button" class="btn btn-lg" style="background-color:Black; color:white">JAVASCRIPT REFERENCE</button>
  </div>
</div>
<div class="row" id="row1">
<div class="column">
  <h1>SQL</h1>
  <p>A language for accessing databases.</p>
  <button type="button" class="btn btn-lg" style="background-color:Black; color:white">LEARN SQL</button>
  <button type="button" class="btn btn-lg" style="background-color:Black; color:white">SQL REFERENCE</button>
</div>
</div>
<div class="row" id="row1">
<div class="column">
  <h1>Data Structure</h1>
  <p>Learn Array,Trees,Graph etc.</p>
  <button type="button" class="btn btn-lg" style="background-color:Black; color:white">START LEARNING</button>
</div>
</div>
<div class="row" id="row1">
<div class="column">
  <h1>Programming Language</h1>
  <p>Learn C,C++,PYTHON,JAVA etc.</p>
  <button type="button" class="btn btn-lg" style="background-color:Black; color:white">START PROGRAMMING</button>
</div>
</div>









</div>


<div class="container-fluid" style="background-color:black; color:white; padding:40px;">
  <b>About Us</b><br>
  Learner is optimized for learning, testing, and training. Examples might be simplified to improve reading and basic understanding. Tutorials, references, and examples are constantly reviewed to avoid errors, but we cannot warrant full correctness of all content. While using this site, you agree to have read and accepted our terms of use, cookie and privacy policy . All Rights Reserved.
</div>









  </body>
</html>
