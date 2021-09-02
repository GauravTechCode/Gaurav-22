 183  projet-1.html 
@@ -0,0 +1,183 @@
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

    <title>Welcome to G.S-world</title>
  </head>
  <body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">G.S</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html">About</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Topic
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="https://www.w3schools.com/whatis/">Web-development</a></li>
                  <li><a class="dropdown-item" href="https://sentry.io/for/android/?utm_source=google&utm_medium=cpc&utm_campaign=9779875595&utm_content=g&utm_term=%2Bandroid%20%2Bapp%20%evelopment&gclid=Cj0KCQjwpreJBhDvARIsAF1_BU1kPC3oEYc3QeM72VlBCZyR1iWzxM13OW7cMfpURDGKguGP_oZcj3QaAg9cEALw_wcB">Android-development</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="https://www.codecademy.com/learn/learn-java/">Java</a></li>
                  <li><a class="dropdown-item" href="https://www.programiz.com/cpp-programming">C++</a></li>

                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="sign-in.html">Sing-in</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>


      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="photo-14-destop.jfif" class="d-block w-100 img-fluid " alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h3 class="text-dark">Welcome to G.S coding world</h3>
              <p class="text-dark">Find Coding Training Faster on Our Site & Save Time </p>
              <!-- <button class="btn btn-danger"></button>
              <button class="btn btn-success"></button>
              <button class="btn btn-light"></button> -->
            </div>
          </div>
          <div class="carousel-item">
            <img src="photo-8.jfif " class="d-block w-100 img-fluid " alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Find It Here</h4>
              <p class="text-dark" ></p>Search For Computer coding courses With Us. Easy to Use</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="photo-9.jfif" class="d-block w-100 img-fluid " alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h4 class="text-dark">Learn coding with us</h4>
              <p class="text-dark">Helping more students learn how to code</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>


      <div class="container my-4">
      <div class="row mb-2">
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-primary">Learn</strong>
              <h3 class="mb-0">Web-Development</h3>
              <div class="mb-1 text-muted">Nov 12</div>
              <p class="card-text mb-auto">Every Web Developer must have a basic understanding of HTML, CSS, and JavaScript. Responsive Web Design is used in all types of modern web development.</p>
              <a href="https://www.geeksforgeeks.org/web-development/" class="stretched-link">Continue reading</a>
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="ptoto-web development-2.jpg" alt="">

            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-success">Learn</strong>
              <h3 class="mb-0">Android-Development</h3>
              <div class="mb-1 text-muted">Nov 11</div>
              <p class="mb-auto">The official site for Android app developers. Provides the Android SDK tools and API documentation.</p>
              <a href="https://developer.android.com/" class="stretched-link">Continue reading</a>
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="photo-android-2.png" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container my-4">
      <div class="row mb-2">
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-primary">Learn</strong>
              <h3 class="mb-0">JavaScript</h3>
              <div class="mb-1 text-muted">Nov 12</div>
              <p class="card-text mb-auto">JavaScript is the world's most popular programming language. JavaScript is the programming language of the Web. JavaScript is easy to learn.</p>
              <a href="https://www.w3schools.com/js/" class="stretched-link">Continue reading</a>
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="photo-js.png" alt="">

            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-success">Learn</strong>
              <h3 class="mb-0">Android-Development</h3>
              <!-- <div class="mb-1 text-muted">Nov 11</div> -->
              <p class="mb-auto">Java is a programming language and a platform. Java is a high level, robust, object-oriented and secure programming language.</p>
              <a href="https://developer.android.com/" class="stretched-link">Continue reading</a>
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="photo-java-3.png" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
    <hr>
    </div>
    <footer class="container">
      <p class="float-end"><a href="#">Back to top</a></p>
      <p >E-mail :- <a href=""> mr.gaurav171@gmail.com </a> - <a href="#" >Privacy</a> - <a href="#">Terms</a></p>
    </footer>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js" integrity="sha384-eMNCOe7tC1doHpGoWe/6oMVemdAVTMs2xqW4mwXrXsW0L84Iytr2wi5v2QjrP/xp" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>
    -->
  </body>
</html>
 BIN +65.3 KB ptoto-web development-2.jpg 
Binary file not shown.
 93  sign-in.html 
@@ -0,0 +1,93 @@
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

    <title>Welcome to G.S world</title>
  </head>

  <body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">G.S</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link " aria-current="page" href="projet-1.html">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html">About</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Topic
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="https://www.w3schools.com/whatis/">Web-development</a></li>
                  <li><a class="dropdown-item" href="https://sentry.io/for/android/?utm_source=google&utm_medium=cpc&utm_campaign=9779875595&utm_content=g&utm_term=%2Bandroid%20%2Bapp%20%2Bdevelopment&gclid=Cj0KCQjwpreJBhDvARIsAF1_BU1kPC3oEYc3QeM72VlBCZyR1iWzxM13OW7cMfpURDGKguGP_oZcj3QaAg9cEALw_wcB">Android-development</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="https://www.codecademy.com/learn/learn-java/">Java</a></li>
                  <li><a class="dropdown-item" href="https://www.programiz.com/cpp-programming">C++</a></li>

                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" href="">Sign-in</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>
      <div class="container" my-5>
      <form>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Email address</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
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
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
      </div>

      <div class="container">
        <hr>
        </div>

      <footer class="container">
        <p class="float-end"><a href="#">Back to top</a></p>
        <p >E-mail :- <a href=""> mr.gaurav171@gmail.com </a> - <a href="#" >Privacy</a> - <a href="#">Terms</a></p>
      </footer>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js" integrity="sha384-eMNCOe7tC1doHpGoWe/6oMVemdAVTMs2xqW4mwXrXsW0L84Iytr2wi5v2QjrP/xp" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>
    -->
  </body>
</html>
