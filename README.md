# Project Responsive Web Design using Bootstrap
# Date:21-05-2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Simplified Dribbble Clone</title>
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  
  <style>
    .hero {
      background-color: #f8f9fa;
      padding: 80px 0;
      text-align: center;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background-color: #212529;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">DribbleClone</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
      data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link active" href="#">Inspiration</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1 class="display-5 fw-bold">Discover the world’s top designers & creatives</h1>
    <p class="lead">Browse thousands of design projects and portfolios.</p>
    <a href="#" class="btn btn-primary btn-lg">Get Inspired</a>
  </div>
</section>

<!-- Gallery Section -->
<section class="py-5">
  <div class="container">
    <h2 class="mb-4 text-center">Featured Shots</h2>
    <div class="row g-4 gallery">
      <div class="col-6 col-md-4 col-lg-3">
        <img src="1.png" alt="Design 1">
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <img src="2.png" alt="Design 2">
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <img src="3.png" alt="Design 3">
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <img src="4.png" alt="Design 4">
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="container">
    <p class="mb-0">Created by Thamizharasi G</p>
  </div>
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:

![Screenshot 2025-05-21 131547](https://github.com/user-attachments/assets/909f39f7-fc02-4cb1-b924-aa288e1e5dd5)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
