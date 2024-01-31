<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  </head>
  <body>
<div>
    <nav class="navbar navbar-dark bg-dark fixed-top" >
        <div class="container-fluid">
          <a class="navbar-brand" href="#"> <img src="https://t4.ftcdn.net/jpg/04/16/71/17/240_F_416711707_qpTNFInsNT5VipN1ciOdhZ6VcE2PrnWY.jpg" alt="Bootstrap" width="40" height="34"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Return</a>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Shopping
                  </a>
                  <ul class="dropdown-menu dropdown-menu-light">
                    <li><a class="dropdown-item" href="#">Men</a></li>
                    <li><a class="dropdown-item" href="#">Women</a></li>
                    <li><a class="dropdown-item" href="#">Kids</a></li>
                    <li><a class="dropdown-item" href="#">Footwear</a></li>
                    <li><a class="dropdown-item" href="#">Cosmetic</a></li>
                    <li><a class="dropdown-item" href="#">Gift Items</a></li>
                    <li>
                      <hr class="dropdown-divider">
                    </li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                  </ul>
                </li>
              </ul>

              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item">
                  <a class="nav-link" href="#">Track Order</a>
                </li>
              </ul>
              <form class="d-flex mt-3" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-success" type="submit">Search</button>
              </form>
            </div>
          </div>
        </div>
      </nav>
      </div>
      

      <div class="container-fluid">
      <h2 style="margin-top:65px; text-align: center;font-family:brush script MT;"><b>K.R General & Readymade Store</b></h2>

      <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel" style="padding-left: 10px;padding-right: 10px;">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000">
            <img src="https://images.unsplash.com/photo-1533642361703-105b1aa2b3ed?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1034&q=80" class="d-block w-100" alt="..." height="550px">
          </div>
          <div class="carousel-item" data-bs-interval="2000">
            <img src="https://images.unsplash.com/photo-1518002171953-a080ee817e1f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80" class="d-block w-100" alt="..." height="550px">
          </div>
          <div class="carousel-item">
            <img src="https://images.unsplash.com/photo-1558505780-1e584fab3ede?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=909&q=80" class="d-block w-100" alt="..." height="550px">
          </div>
          <div class="carousel-item">
            <img src="https://images.unsplash.com/photo-1514090458221-65bb69cf63e6?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=870&q=80" class="d-block w-100" alt="..." height="550px">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      </div>
      <br>

<div class="container" style="padding-left: 10px;padding-right: 10px;">
  <div class="row text-center">
  <div class="col-lg-4">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1630861460368-5620bd06adfd?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=876&q=80" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Footwear</h5>
      <p class="card-text">You can wear anything as long as you put a nice pair of shoes with it.</p>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>

<div class="col-lg-4">
  <div class="card">
    <img src="https://cdn.igp.com/f_auto,q_auto,t_pnopt10prodlp/products/p-personalized-ceramic-planters-109091-m.jpg" class="card-img-top" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Gift Items</h5>
      <p class="card-text">Some gift are big. Others are small. But the ones that come from the heart are the best gifts of all.</p>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>

<div class="col-lg-4">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1522338242992-e1a54906a8da?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8Y29zbWV0aWN8ZW58MHx8MHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Cosmetic</h5>
      <p class="card-text">"Sometimes you just have to put on lip gloss and pretend to be psyhed."..</p>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>
</div>
</div>
<br>



<div class="container mt-5">
  <div class="row">
    <div class="col-lg-6">
      <img src="https://images.pexels.com/photos/5709226/pexels-photo-5709226.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="..." height="100%">
      <div class="card-body">
        <h5 class="card-title"  style="color: brown;font-size: xx-large;">Summer Clothes</h5>
        <a href="#" class="btn btn-primary">For More...</a>
      </div>
    </div>


    

    <div class="col-lg-6">
        <img src="https://images.pexels.com/photos/6617770/pexels-photo-6617770.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="..."height="100%">
        <div class="card-body">
          <h5 class="card-title" style="color: brown;font-size: xx-large;">Winter Clothes</h5>
          <a href="#" class="btn btn-primary">For More...</a>
        </div>
      </div> 
  </div>
</div>
<br>
<br>
<br>
<hr>

<div class="container" style="padding-left: 10px;padding-right: 10px;">
  <div class="row text-center">
  <div class="col-lg-4">
  <div class="card">
    <img src="https://images.pexels.com/photos/325527/pexels-photo-325527.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title" style="color: brown;"><b>Jewellery</b></h5>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>

<div class="col-lg-4">
  <div class="card">
    <img src="https://images.pexels.com/photos/15005105/pexels-photo-15005105/free-photo-of-cosmetic-product-in-black-canister.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title" style="color: brown;"><b>Body Spray</b></h5>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>

<div class="col-lg-4">
  <div class="card">
    <img src="https://images.pexels.com/photos/17912592/pexels-photo-17912592/free-photo-of-woman-posing-with-a-luxury-orange-purse.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title" style="color: brown;"><b>Purse, Belt</b></h5>
      <a href="#" class="btn btn-primary">For More...</a>
    </div>
</div>
</div>
</div>
</div>


<div class="container mt-4">
  <hr>
  <div class="row">
    <div class="col-sm-6">
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d1750517.5864517696!2d75.4110207!3d31.026816300000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sin!4v1692260178878!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>

      <div class="col-sm-6" style="padding-left: 50px;padding-right: 50px;margin-top: 20px;">
      <form class="row g-3">
        <div class="row">
        <div class="col-sm-14">
          <marquee>
            <h3 style="color: brown;">ADDITIONAL 10% DISCOUNT ON HDFC CARD</h3>
          </marquee>
          </div>
          </div>
        <div class="col-md-4">
          <label for="validationServer01" class="form-label">First name</label>
          <input type="text" class="form-control is-valid" id="validationServer01" value="First Name" required>
          <div class="valid-feedback">
            Looks good!
          </div>
        </div>
        <div class="col-md-4">
          <label for="validationServer02" class="form-label">Last name</label>
          <input type="text" class="form-control is-valid" id="validationServer02" value="Last Name" required>
          <div class="valid-feedback">
            Looks good!
          </div>
        </div>
        <div class="col-md-4">
          <label for="validationServerUsername" class="form-label">Username</label>
          <div class="input-group has-validation">
            <span class="input-group-text" id="inputGroupPrepend3">@</span>
            <input type="text" class="form-control is-invalid" id="validationServerUsername" aria-describedby="inputGroupPrepend3 validationServerUsernameFeedback" required>
            <div id="validationServerUsernameFeedback" class="invalid-feedback">
              Please choose a username.
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <label for="validationServer03" class="form-label">Contact no.</label>
          <input type="number" class="form-control is-invalid" id="validationServer03" aria-describedby="validationServer03Feedback" required>
          <div id="validationServer03Feedback" class="invalid-feedback">
            Please provide a valid number.
          </div>
        </div>
        <div class="col-md-3">
          <label for="validationServer04" class="form-label">City</label>
          <select class="form-select is-invalid" id="validationServer04" aria-describedby="validationServer04Feedback" required>
            <option selected disabled value="">Choose...</option>
            <option>...</option>
          </select>
          <div id="validationServer04Feedback" class="invalid-feedback">
            Please select a valid city.
          </div>
        </div>
        <div class="col-md-3">
          <label for="validationServer05" class="form-label">Pin Code</label>
          <input type="number" class="form-control is-invalid" id="validationServer05" aria-describedby="validationServer05Feedback" required>
          <div id="validationServer05Feedback" class="invalid-feedback">
            Please provide a valid pin code.
          </div>
        </div>
        <div class="col-12">
          <div class="form-check">
            <input class="form-check-input is-invalid" type="checkbox" value="" id="invalidCheck3" aria-describedby="invalidCheck3Feedback" required>
            <label class="form-check-label" for="invalidCheck3">
              Agree to terms and conditions
            </label>
            <div id="invalidCheck3Feedback" class="invalid-feedback">
              You must agree before submitting.
            </div>
          </div>
        </div>
        <div class="col-12">
          <button class="btn btn-primary" type="submit">Submit form</button>
        </div>
      </form>
      </div>


    </div>
  </div>

<div class="container">
  <hr>
  <div style="display: flex; justify-content: center;">
      <div style="padding-left: 10px;">
        <img src="https://cdn-icons-png.flaticon.com/128/733/733585.png" height="50">
        </div>

        <div style="padding-left: 10px;">
          <img src="https://cdn-icons-png.flaticon.com/128/145/145802.png" height="50">
          </div>

          <div style="padding-left: 10px;">
            <img src="https://cdn-icons-png.flaticon.com/128/281/281764.png" height="50">
            </div>

            <div style="padding-left: 10px;">
              <img src="https://cdn-icons-png.flaticon.com/128/3955/3955024.png" height="50">
              </div>
    </div>
  </div>

<div class="container">
  <div class="row" style="padding-top: 20px;">
    <div class="col-sm-3">
      <h3 style="padding-left: 40px; text-align: center;">K.R GENERAL<hr></h3>
      <p style="text-align: center;">All Kinds of Bombay <br>artificial <br>jewellery,Gift<br> Items,Branded <br>Kids,Gents<br> Readymade and <br>others.</p>
    </div>

    <div class="col-sm-3">
      <h3 style="padding-left: 40px;text-align: center;">PRODUCTS<hr></h3>
      <p style="text-align: center;color: blue;">Readymade<br>Footwear<br>Gift Items <br>Additional<br>Items </p>
    </div>

    <div class="col-sm-3">
      <h3 style="padding-left: 40px;text-align: center;">USEFUL LINKS <hr></h3>
      <p style="color: blue;text-align: center;">Your Account<br>Track Your Order<br>Shopping Rates<br>Help</p>
    </div>

    <div class="col-sm-3">
      <h3 style="padding-left: 40px;text-align: center;">CONTACT<hr></h3>
      <p style="text-align: center;">Vill.Mari-Mustafa,Teh Bagha<br>Purana,Moga,Pin-142049,IND<br></p>
      <p style="text-align: center;">Karanguglani@gmail.com<br></p>
      <p style="text-align: center;">+919814211213,+916284895404</p>
    </div>

  </div>
  </div>


  <div class="container">
    <div class="footer-copyright text-center py-3 bg-dark">
        <span style="color: rgb(255, 255, 255);">© 2021 Copyright:<a href>karanguglani20@gmail@gmail.com</a></span>
  </div>
  </div> 






      
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>

</body>
</html>
