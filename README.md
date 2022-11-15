<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/bootstrap.css">
        <link rel="stylesheet" href="css/bootstrap-responsive.css">
        <link rel="stylesheet" href="css/font-awesome.css">
        <link rel="stylesheet" href="css/app.css">
        <!--[if IE 7]>
            <link rel="stylesheet" href="css/font-awesome-ie7.min.css">
        <![endif]-->
        <script src="https://kit.fontawesome.com/072f9738c5.js" crossorigin="anonymous"></script>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.6/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
    <script src="https://kit.fontawesome.com/44768aa605.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>🌺 Flowers</title>
    <style>
        body{
        }
        #carouselExampleIndicators{
            margin-top: 0.5%;
        }
        #secur{
            display: flex;
            justify-content: center;
            justify-content: space-evenly;

        }
        .card{
          position: relative;
          top: 0;
          transition: top ease 0.5s;
        }
        .card:hover{
          top: -10px;
          box-shadow: 5px 5px 5px 5px;
        }
        div.card-deck{
          margin-top: 5%;
          margin-left: 10%;
          margin-right: 10%;
        }
        h4{
          position: relative;
          color: rgb(160, 46, 46);
          transition: top ease 1s;
        }
        h4:hover{
          color: black;
          top: -5px;
        }
        #more{
          text-decoration: none;
          color: inherit;
          position: relative;
          transition: top ease 0.5s;
        }
        #more:hover{
          text-decoration: none;
          color: inherit;
          top: -5px;
        }



        
    </style>
</head>
<body>
  <header>
    <nav style="background-color: #3A8891;color: white;" class="navbar navbar-expand-lg navbar-light">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
            <li class="nav-item active">
              <a class="nav-link" href="#"><b>&nbsp;&nbsp;Home </b><span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="bouquets.html">&nbsp;&nbsp;<b>Wedding Bouquets</b></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="contact.html">&nbsp;&nbsp;<b>Party Bouquets</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="contact.html">&nbsp;&nbsp;<b>Anniversary Bouquets</b></a>
              </li>
            <li class="nav-item">
                <a class="nav-link" href="order.html">&nbsp;&nbsp;<b>Track Order</b></a>
              </li>
            <li class="nav-item">
              <a class="nav-link" href="about.html">&nbsp;&nbsp;<b>About Us</b></a>
            </li>
          </ul>
          
        </div>
        
        
        <a href="cart.html" style="color: white;"><i class="fa-solid fa-cart-shopping"></i></a>
        
        </header>



      </nav>
      <marquee>available in lucknow.</marquee>

      <div class="table-responsive">
      <table class="table">
        <thead>
          <tr>
            <th scope="col" style="text-align: center;"><i class="fa-solid fa-truck-fast"></i>India</th>
            <th scope="col" style="text-align: center;"><i class="fa-solid fa-phone"></i>+910123456789</th>
            <th scope="col" style="text-align: center;">&nbsp;Offers %</th>
          </tr>
        </thead>
        </table>
      </div>

      <form style="justify-content: center;" class="form-inline my-2 my-lg-0"><span style="display:flex;">
        
        <input style="margin-top: 0%;margin-bottom: 2.5%;"class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <span style="margin-left: 5%;margin-top:0%;margin-bottom: 2.5%;"><button class="btn btn-outline-dark my-2 my-sm-0" type="submit">Search</button></span>
    </span>
      </form>
      
      
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="600.jpg"  alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="hap.webp"  alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="li.jpg"  alt="Third slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span style="background-color: none;" class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span  class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span style="background-color: none;" class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>


      <h4 style="margin-top: 5%;text-align:center;font-family: 'Times New Roman', Times, serif;">Flowers for your LOved Ones</h4>
      <br><p style="text-align: right;margin-right: 12%;"><a href="flowers.html" id="more"><span style="text-align: right;">View All</span></a></p>
      <hr style="margin-right: 12%;margin-left:12%;">
      
      <div class="card-deck">
        
        <div class="card">
          <a href="cart.html"><img class="card-img-top" src="demo2.jpeg"></a>
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Rose Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.499</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>



          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="demo5.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Luxury Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.599</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="demo3.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Yellow Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.549</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="demo4.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">White Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.699</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
      </div>



      <h4 style="margin-top: 5%;text-align:center;font-family: cursive;">Pure & Auspicious</h4>
      <br><p style="text-align: right;margin-right: 12%;"><a href="flowers.html" id="more"><span style="text-align: right;">View All</span></a></p>
      <hr style="margin-right: 12%;margin-left:12%;">


      <div class="card-deck">
        <div class="card">
          <img class="card-img-top" src="pink.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Pink Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.849</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="or.jpeg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Orchid Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.999</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="mix.png" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">Mixed Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.699</p></p>
            <button type="button" class="btn btn-warning" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="wh.webp" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title" style="text-align: center;">White Bouquet</h5>
            <p class="text-muted" style="text-align: center;">Defines Love, Passion, Beauty & Respect.</p>
            <p class="card-text"><p style="text-align: center;">Rs.899</p></p>
  <button type="button" class="btn btn-warning add-to-cart" style="display: flex;margin: auto;">Add to Cart</button>

          </div>
        </div>
      </div>

      <div class="select"></div>

<br><br>
      <p style="text-align: center;">Follow us on 
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-twitter"></i>
        /@Flowersforyou
      </p>

      <p style="background-color: black;color:white;text-align: center;">
        Terms of Use | Disclaimer | Privacy Policy | Feedback</p>



</body>
</html>
