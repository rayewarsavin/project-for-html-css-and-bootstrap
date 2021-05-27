<!DOCTYPE html>
<html>
<head>
	<title>portfolio website</title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
	
<!---navbar----->
  <nav class="navbar navbar-expand-lg navbar-light bg-warning sticky-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Savin</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#skills">My skills</a>
        </li>
         
         <li class="nav-item">
          <a class="nav-link" href="#works">My work </a>
        </li>
        
      

        <li class="nav-item">
          <a class="nav-link" href="#contact">contact Us</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-danger" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>


<main class="containe mt-3"  >
  <section id="hero" class=" d-flex justify-content-sm-center 
  justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
    <!-----hero--->
    

    <div class="d-flex justify-content-sm-center align-items-center flex-column
    flex-md-column ">
      <h5>Hii 👋</h5>
      <h1>i'am John abraham</h1>
      <p>A computer science student</p>
      <button class="btn btn-primary btn-sm">my cool resume 😎</button>
   </div>

   <div class=" d-md-none w-50 h-50 ">
   <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQEZrATmgHOi5ls0YCCQBTkocia_atSw0X-Q&usqp=CAU" alt="john abraham" class=" w-100 h-100 rounded-circle shadow-lg ">
   </div>
   <div class="d-none d-md-block w-25 h-25"> 
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQEZrATmgHOi5ls0YCCQBTkocia_atSw0X-Q&usqp=CAU" alt="john abraham" class=" w-100 h-100 rounded-circle shadow-lg "> 

   </div>
  </section>

  <section id="skills" class=" mt-5  pd-4 rounded ">
  <!---------my skills--------->

<h1 class="text-primary text-center">my skills</h1>
 
 <div class=" mt-4 d-flex  d-md-none justify-content-evenly" >
  <i class="fab fa-html5 fa-3x text-danger"></i>
 <i class="fab fa-css3-alt fa-3x text-primary"></i>
  <i class="fab fa-bootstrap fa-3x text-info"></i>
</div>
<div class=" mt-4 d-none d-md-flex  justify-content-md-evenly" >
  <i class="fab fa-html5 fa-7x text-danger"></i>
 <i class="fab fa-css3-alt fa-7x text-primary"></i>
  <i class="fab fa-bootstrap fa-7x text-info"></i>
</div>

</section>


<section id="works" class=" mt-5  pd-4 rounded text-center ">
<!--------my works------>

<h1 class="text-danger">my works</h1>
<div class="card mt-3" >
  <img src="https://images.unsplash.com/photo-1496171367470-9ed9a91ea931?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">progrtamig world</h5>
    <p class="card-text">build an amazing website with the help of bootstrap.</p>
    <a href="#" class="btn btn-dark">Go somewhere </a>
  </div>
</div>

</section>

<section  id="contact" class="mt-4 py-4" >
<!------contact us------>

  <form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" required class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-warning">Submit</button>
</form>
<div>
  
  <h3>@gmail.com</h3>
</div>


</section>

</main>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

</body>
</html>
