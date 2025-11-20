# Project Responsive Web Design using Bootstrap
## Date: 20/11/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Travel Destinations</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"rel="stylesheet">
  <style>
    .shot-card img {
      height: 200px;
      object-fit: cover;
    }
    .shot-card:hover {
      transform: scale(1.02);
      transition: transform 0.15s ease;
    }
  </style>
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">WanderWorld</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Destinations</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Login</a></li>
        <form class="d-flex me-3" role="search">
          <input class="form-control me-2" type="search" placeholder="Search places" aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
      </ul>
    </div>
  </div>
</nav>
<div class="container mt-4">
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="ba.jpg" class="card-img-top" alt="Bali">
        <div class="card-body">
          <h5 class="card-title">Bali, Indonesia</h5>
          <p class="card-text">Tropical paradise with beautiful beaches.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="paristo.jpg" class="card-img-top" alt="Paris">
        <div class="card-body">
          <h5 class="card-title">Paris, France</h5>
          <p class="card-text">City of love and lights, home to the Eiffel Tower.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="Tokyo.jpg" class="card-img-top" alt="Tokyo">
        <div class="card-body">
          <h5 class="card-title">Tokyo, Japan</h5>
          <p class="card-text">Vibrant city blending tradition and technology.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="GrandCanyon.jpg" class="card-img-top" alt="Grand Canyon">
        <div class="card-body">
          <h5 class="card-title">Grand Canyon, USA</h5>
          <p class="card-text">Majestic natural wonder carved by the Colorado River.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="Santorini.jpg" class="card-img-top" alt="Santorini">
        <div class="card-body">
          <h5 class="card-title">Santorini, Greece</h5>
          <p class="card-text">Whitewashed houses and stunning sunsets.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="SwissAlps.jpg" class="card-img-top" alt="Swiss Alps">
        <div class="card-body">
          <h5 class="card-title">Swiss Alps, Switzerland</h5>
          <p class="card-text">Snow-capped peaks and scenic trails.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="Machupicchu.jpg" class="card-img-top" alt="Machu Picchu">
        <div class="card-body">
          <h5 class="card-title">Machu Picchu, Peru</h5>
          <p class="card-text">Ancient Incan citadel nestled in the Andes.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="vic.jpg" class="card-img-top" alt="Venice">
        <div class="card-body">
          <h5 class="card-title">Venice, Italy</h5>
          <p class="card-text">Romantic canals and Renaissance architecture.</p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card shot-card">
        <img src="Dubai.jpg" class="card-img-top" alt="Dubai">
        <div class="card-body">
          <h5 class="card-title">Dubai, UAE</h5>
          <p class="card-text">Modern luxury meets desert adventure.</p>
        </div>
      </div>
    </div>
  </div>
</div>
<footer class="mt-5">
  <h2 style="background-color: #1a3635; color: white; text-align: center; font-size: 18px; font-family: 'Trebuchet MS', sans-serif;">
    Designed and developed by Pakanati Monish
  </h2>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
<img width="1315" height="611" alt="Screenshot 2025-11-20 104441" src="https://github.com/user-attachments/assets/ccdc96fe-526e-4d6b-8f05-9d154b4e0c59" />

<img width="1320" height="396" alt="Screenshot 2025-11-20 104500" src="https://github.com/user-attachments/assets/facfc297-bbfa-4ab4-b0de-ba4daf224bff" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
