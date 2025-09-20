# Javascript-final-project-

html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>A Charming Responsive Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">MySite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-4 fw-bold">Welcome to MySite</h1>
      <p class="lead">A charming little webpage built with Bootstrap 5</p>
      <button class="btn btn-primary btn-lg mt-3">Get Started</button>
    </div>
  </section>

  <section>
    <div id="mainCarousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="0" class="active"></button>
        <button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="1"></button>
        <button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="2"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://via.placeholder.com/1200x500" class="d-block w-100" alt="Slide 1">
          <div class="carousel-caption d-none d-md-block">
            <h5>First Slide</h5>
            <p>A delightful introduction, the first of many!</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://via.placeholder.com/1200x500" class="d-block w-100" alt="Slide 2">
          <div class="carousel-caption d-none d-md-block">
            <h5>Second Slide</h5>
            <p>Your journey continues with this lovely view.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://via.placeholder.com/1200x500" class="d-block w-100" alt="Slide 3">
          <div class="carousel-caption d-none d-md-block">
            <h5>Third Slide</h5>
            <p>An enchanting sight to wrap up this carousel!</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#mainCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#mainCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
    </div>
  </section>

  <section class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-6">
          <img src="https://via.placeholder.com/600x400" alt="Placeholder" class="img-fluid rounded shadow">
        </div>
        <div class="col-md-6 d-flex align-items-center">
          <div>
            <h2>A Responsive Image</h2>
            <p class="text-muted">This image dances to your screen's size thanks to Bootstrap’s <code>img-fluid</code> class.</p>
            <a href="#" class="btn btn-outline-dark">Learn More</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-light py-5">
    <div class="container">
      <h2 class="text-center mb-5">Our Services</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <img src="https://via.placeholder.com/400x250" class="card-img-top" alt="Service 1">
            <div class="card-body">
              <h5 class="card-title">Service One</h5>
              <p class="card-text">A fine description of our first service, crafted with care.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <img src="https://via.placeholder.com/400x250" class="card-img-top" alt="Service 2">
            <div class="card-body">
              <h5 class="card-title">Service Two</h5>
              <p class="card-text">An enticing glimpse into our second offering.</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <img src="https://via.placeholder.com/400x250" class="card-img-top" alt="Service 3">
            <div class="card-body">
              <h5 class="card-title">Service Three</h5>
              <p class="card-text">A peek into our third service, which may just be the one for you!</p>
              <a href="#" class="btn btn-primary">Read More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-light text-center py-4 mt-5">
    <div class="container">
      <p class="mb-0">&copy; 2025 MySite. All rights reserved, and all delighted!</p>
      <small>Designed with a sprinkle of magic from Bootstrap 5</small>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
