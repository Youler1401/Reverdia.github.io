<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" type="text/css" href="estilo.css">
  <link rel="icon" type="text/css" href="imagenes/reverdiaico.ico">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <title>Reverdia</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    



    <header>
<nav class="navbar navbar-expand-sm  ">
  <div class="container-fluid">
    <a class="navbar-brand" href="index.html"><img class="lg1"src="imagenes/reverdia.jpeg"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mynavbar">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
        <a class="tex1" class="nav-link" href="Chocolinos.html">Chocolinos</a>
        </li>
        <li class="nav-item">
          <a class="tex1"class="nav-link" href="Saman.html">Saman</a>
        </li>
        <li class="nav-item">
          <a class="tex1"class="nav-link" href="Sutra.html">Sutra</a>
        </li>
        <li class="nav-item"></li>
          <a class="tex1" class="nav-link" href="contactenos.html">Contactenos</a>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="text" placeholder="Buscar">
        <button class="btn btn-outline-warning" type="button">Buscar</button>
      </form>
    </div>
  </div>
</nav>
  </header> 




  <!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="carrusel" src="imagenes/saman.jpeg" style="width:100%">
    </div>
    <div class="carousel-item">
      <img class="carrusel" src="imagenes/chocolinosbanner2.jpeg" style="width:100%">
    </div>
    <div class="carousel-item">
      <img class="carrusel" src="imagenes/chocolinosbanner.jpeg"style="width:100%">
    </div>
     <div class="carousel-item">
      <img class="carrusel" src="imagenes/sutra.jpeg"style="width:100%">
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
  <!-- Carousel wrapper -->
<div
  id="carouselMultiItemExample"
  class="carousel slide carousel-dark text-center"
  data-mdb-ride="carousel"
>
  <!-- Controls -->
  
  <!-- Inner -->
  <div class="carousel-inner py-4">
    <!-- Single item -->
    <div class="carousel-item active">
      <div class="container">
        <div class="row">
          <div class="col-lg-4">
            <div class="card">
              <img class="img" 
                src="imagenes/choccolinos.jpg"
              />
              <div class="card-body">
                <h5 class="card-title">ChoColinos</h5>
                <p class="card-text">
                  Nuestros productos de chocolinos vienen siendo comida
                </p>
                <a href="ChoColinos.html" class="btn btn-warning">Mas Informacion</a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 d-none d-lg-block">
            <div class="card">
              <img class="img" 
                src="imagenes/logosaman.jpeg"
              />
              <div class="card-body">
                <h5 class="card-title">Saman</h5>
                <p class="card-text">
                  Saman nos ofrece productos medicinales a base de coca y marihuana
                </p>
                <a href="Saman.html" class="btn btn-warning">Mas Informacion</a>
              </div>
            </div>
          </div>

          <div class="col-lg-4 d-none d-lg-block">
            <div class="card">
              <img class="img" 
                src="imagenes/logosutra.jpeg"
              />
              <div class="card-body">
                <h5 class="card-title">Sutra</h5>
                <p class="card-text">
                  Sutra nos ofrece productos medicinales a base de coca y marihuana
                </p>
                <a href="Sutra.html" class="btn btn-warning">Mas Informacion</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>
<a href="https://wa.me/573108752786?text=Me%20gustaría%20saber%20el%20precio%20de%20los%20prodcutos" class="whatsapp" target="_blank"> <i class="fa fa-whatsapp whatsapp-icon"></i></a> 
<!-- Carousel wrapper -->
<!-- Footer -->







<footer class="text-center text-lg-start bg-body-tertiary text-muted">
  <section class="">
    <div class="container text-center text-md-start mt-5">
      <!-- Grid row -->
      <div class="row mt-3">
        <!-- Grid column -->
        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
          <!-- Content -->
          <h6 class="text-uppercase fw-bold mb-4">
            <i class="fas fa-gem me-3"></i>Reverdia
          </h6>
          <p>
            Somos una empresa Colombiana que lleva en el mercado alrededor de 7 años, dedicada al cultivo y produccion agroecologica de derivados de plantas, prcipalmente la coca y marihuana
          </p>
        </div>
        <!-- Grid column -->

        <!-- Grid column -->
        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">
            Marcas
          </h6>
          <p>
            <a href="chocolinos.html" class="text-reset">Chocolinos</a>
          </p>
          <p>
            <a href="Saman.html" class="text-reset">Saman</a>
          </p>
          <p>
            <a href="Sutra.html" class="text-reset">Sutra</a>
          </p>
        </div>
       <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
          <!-- Links -->
          <h6 class="text-uppercase fw-bold mb-4">Contacto</h6>
          <p> Bogota,Colombia </p>
          <p> chocolinos@gmail.com</p>
          <p> +57 3108752686</p>
          <p> +57 3059229464</p>
        </div>


      </div>
    
       
  </section>
 


</footer>
<!-- Footer -->
</body>
</html>
