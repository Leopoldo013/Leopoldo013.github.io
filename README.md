<!DOCTYPE html>
<html lang=pt dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Mago Lukian</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Montserrat|Ubuntu&display=swap" rel="stylesheet">

  <!-- CSS Stylesheets -->
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

  <!-- Font Awesome -->
  <script defer src="https://use.fontawesome.com/releases/v5.0.7/js/all.js"></script>

  <!-- Bootstrap Scripts -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

</head>

<body>
  <section id="titulo">

    <div class="container-fluid">

      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-md navbar-dark">
        <a class="navbar-brand" href="#testimonials">Mago Lukian</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">
                Contato
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#pricing">
                Preços
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#cta">
                Download
              </a>
            </li>
          </ul>
        </div>
      </nav>



      <!-- Titulo -->

      <div class="row">

        <div class="col-lg-6">
          <h1 id="fonth"><b>Um dos maiores magicos da atualidade.</b></h1>
          <button type="button" class="btn btn-outline-light ">Contrate</button>
        </div>

        <div class="col-lg-6">
          <img class="image" src="image/magica.png" alt="cartola">
        </div>
      </div>
    </div>

  </section>

  <!-- Caracteristicas -->

  <section id="caracteristicas">

    <div class="row">


      <div class="box col-lg-4">
        <i class="icon fas fa-magic fa-4x"></i>
        <h3>Close-up.</h3>
        <p>O melhor da magica de contato.</p>
      </div>

      <div class="box col-lg-4">
        <i class="icon fas fa-magic fa-4x"></i>
        <h3>Mentalismo.</h3>
        <p>Incríveis feitos mentais.</p>
      </div>

      <div class="box col-lg-4">
        <i class="icon fas fa-magic fa-4x "></i>
        <h3>Hipnose.</h3>
        <p>O melhor da hipnose de palco.</p>
      </div>

    </div>
  </section>

  <!-- Testemunhos -->

  <section id="testemunhos">

    <div id="carousel-testemunhos" class="carousel slide" data-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="testimonial-text">Magicas incriveis, com bom humor e respeito otimo profissional. Super recomendo!!!</h2>
          <img class="testimonial-image" src="image/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, Barueri</em>
        </div>
        <div class="carousel-item">
          <h2 class="testimonial-text">O melhor da hipnose de palco e mentalismo da atualidade. Profissional completo!!!.</h2>
          <img class="testimonial-image" src="image/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Carapicuiba</em>
        </div>
        <a class="carousel-control-prev" href="#carousel-testemunhos" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carousel-testemunhos" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>





  </section>

  <!-- Pacotes de Preços -->

  <section id="preços">

    <h2 id="font-h2">Contrate para seu evento</h2>
    <p>Preços que cabem no seu bolso.</p>

    <div class="row">
      <div class="preço-coluna col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Infantil</h3>
          </div>
          <div class="card-body">
            <h2>R$500/1h.</h2>
            <p>Esculturas com bixigas</p>
            <p>45 min de evento no palco</p>
            <p>15 de magicas on the table</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Contrate</button>
          </div>
        </div>
      </div>
      <div class="preço-coluna col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Adultos</h3>
          </div>
          <div class="card-body">
            <h2>R$750 / 1h.</h2>
            <p>45min. de evento no palco.</p>
            <p>30min hipnose palco</p>
            <p>15 min. magicas on the table</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Contrate</button>
          </div>
        </div>
      </div>
      <div class="preço-coluna col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Palestras</h3>
          </div>
          <div class="card-body">
            <h2>R$1000 / 1h</h2>
            <p>Comunicação eficiente</p>
            <p>Motivação</p>
            <p>Auto-hipsone</p>
            <p>Hipnose não verbal</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Contrate</button>
          </div>
        </div>
      </div>

    </div>


  </section>

  <footer id="roda-pe">
    <i class="social-icon fab fa-facebook-f"></i>
    <i class="social-icon fab fa-instagram"></i>
    <i class="social-icon fab fa-twitter"></i>
    <i class="social-icon fas fa-envelope"></i>
    <p>© Copyright 2019 Mago Lukian</p>

  </footer>

</body>

</html>
