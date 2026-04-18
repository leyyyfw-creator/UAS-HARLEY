# UTS-HARLEY
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Trusted Paws</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css?family=Poppins:wght@300;400;500;600;700&display=swap"
    rel="stylesheet">
    <!-- External CSS -->
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg py-3">

        <div class="container">

            <a class="navbar-brand d-flex align-items-center gap-2" href="#">
                <span class="fw-bold">Trusted<span class="text-primary">Paws</span></span>
            </a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
                <span class="navbar-toggler-icon"></span>
            </button>

        <div class="collapse navbar-collapse justify-content-center" id="navMenu">

            <ul class="navbar-nav gap-lg-4">

                <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Collection</a></li>
                <li class="nav-item"><a class="nav-link" href="#">All Pet</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>

            </ul>

        </div>
        <div class="d-none d-lg-block">
            <a href="#" class="btn btn-dark rounded-pill px-4">Login</a>
        </div>
    </nav>
<!-- Hero -->
<section class="hero py-5">
    <div class="container text-center">
        
        <div class="row justify-content-center">
            <div class="col-lg-8">

                <h1 class="hero-title mb-3">
                    Your Trusted Place to Meet Your New Best Friend
                </h1>
                <p class="hero-subtitle mb-4">
                    Carefully selected pets, ready to bring joy to your home.
                </p>
                <a href="#" class="btn btn-primary btn-hero">
                    Get Started Now
                    <span class="ms-2 circle-next">></span>
                </a>
            </div>
        </div>

        <!-- Cards -->
        <div class="row mt-6 justify-content-center align-items-end g-4">
            
            <div class="col-10 col-md-3">
                <div class="pet-card bg-pink relative">
                    <img src="assets/images/dog2.png" class="img-fluid img-absolute" alt="dog1">
                </div>
            </div>

            <div class="col-10 col-md-3">
                <div class="pet-card bg-purple relative">
                    <img src="assets/images/dog1.png" class="img-fluid img-absolute" alt="dog2">
                </div>
            </div>
    
            <div class="col-10 col-md-3">
                <div class="pet-card bg-yellow relative">
                    <img src="assets/images/dog3.png" class="img-fluid img-absolute" alt="dog3">
                </div>
            </div>

        </div>

    </div>
    </section>
</body>
</html>
