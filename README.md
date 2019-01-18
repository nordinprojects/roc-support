# roc-support
<?php
include('bootstrap.php');
session_start();


?>

<!DOCTYPE html>
<html lang="en">

  <head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>Amstelsupport</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom fonts for this template -->
    <link href="https://fonts.googleapis.com/css?family=Catamaran:100,200,300,400,500,600,700,800,900" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Lato:100,100i,300,300i,400,400i,700,700i,900,900i" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/one-page-wonder.min1.css" rel="stylesheet">
    <link rel="shortcut icon" href="favicon.ico">
    
   

  </head>

  <body>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark navbar-custom fixed-top">
      <div class="container">
        <img src="rocva.png" class="image1" alt="avatar"></img>
        <a class="navbar-brand" href="#">Amstelsupport</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <?php if (isset($_SESSION['gebruikersnaam'])){ 
              echo "<a class=nav-link href=logout.phtml>Log out</a>"; }
              
              else{
                echo "<a class=nav-link href=login.phtml>Log in</a>";
              }
              ?>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <header class="masthead text-center text-white">
      <div class="masthead-content">
        <div class="container">
          <h1 class="masthead-heading mb-0">Voor Je Meldingen & Gevonden Voorwerpen</h1>
          <h2 class="masthead-subheading mb-0">Amstelsupport</h2>
          <a href="melding.phtml" class="btn btn-primary btn-xl rounded-pill mt-5">Melding</a>
          <a href="Lost&Found.phtml" class="btn btn-primary btn-xl rounded-pill mt-5">Lost&Found</a>
        </div>
      </div>
      <div class="bg-circle-1 bg-circle"></div>
      <div class="bg-circle-2 bg-circle"></div>
      <div class="bg-circle-3 bg-circle"></div>
      <div class="bg-circle-4 bg-circle"></div>
    </header>

    <section>
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6 order-lg-2">
            <div class="p-5">
              <img class="img-fluid rounded-circle" src="storing.png" alt="">
            </div>
          </div>
          <div class="col-lg-6 order-lg-1">
            <div class="p-5">
              <h2 class="display-4">STUDENTINFO - Vertraging bij uitgifte van nieuwe schoolpas</h2>
              <p>Door een storing in het pasjessysteem kunnen wij niet de schoolpas voor nieuwe studenten op Amstelland printen. Wij werken er hard aan om het probleem op te lossen. Je mentor houdt je op de hoogte van de voortgang. 
                <p>Onze excuses voor het ongemak.</p> <p> Team Facilitair</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6">
            <div class="p-5">
              <img class="img-fluid rounded-circle" src="hbo.jpg" alt="">
            </div>
          </div>
          <div class="col-lg-6">
            <div class="p-5">
              <h2 class="display-4">STUDENTINFO - Doe mee aan HBO Skills campagne!</h2>
              <p>Ben jij een ambitieus en enthousiaste student én wil je ervaren hoe het is om mee te werken aan een echte communicatiecampagne? Meld je vóór 17 september aan via c.fierant@rocva.nl met daarin je 06-nummer en je foto. Mijn naam is Caroline Fierant, communicatiemanager van deze school. Ik zoek 10 studenten, serieus!</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6 order-lg-2">
            <div class="p-5">
              <img class="img-fluid rounded-circle" src="devano.jpeg" alt="">
            </div>
          </div>
          <div class="col-lg-6 order-lg-1">
            <div class="p-5">
              <h2 class="display-4">STUDENTINFO - Check-it!</h2>
              <p>Weet jij wat je eigen risico inhoudt, hoeveel uur slaap je moet pakken en wat het verschil is tussen pesten en plagen? Antwoord op deze (en een heleboel andere) vragen vind je op Check it. Om de kennis over deze onderwerpen te testen, nodigden we Défano Holwijn uit. Hij stelde een aantal rake vragen. Hoe dat eraan toeging? Check de vlog hieronder.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-5 bg-black">
      <div class="container">
        <p class="m-0 text-center text-white small">Copyright &copy; Your Website 2018</p>
      </div>
      <!-- /.container -->
    </footer>

    <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

  </body>

</html>

