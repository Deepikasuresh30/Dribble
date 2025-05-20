# Project Responsive Web Design using Bootstrap
## Date: 20.05.2025

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
  <title>Dribbble Shots Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: #f8f9fa;
    }
    .shot-card img {
      border-radius: 10px;
      width: 100%;
      height: auto;
      object-fit: cover;
    }
    .navbar {
      background-color: #333;
    }
    .navbar-brand, .nav-link, .navbar-text {
      color: #fff !important;
    }
    footer {
      background-color: #212529;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">Dribbble</a>
    <div class="collapse navbar-collapse justify-content-end">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
        <li class="nav-item"><a class="nav-link btn btn-outline-light ms-2" href="#">Sign up</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Header -->
<div class="text-center py-4">
  <h2 class="fw-bold">Explore Trending Shots</h2>
  <p class="text-muted">Beautiful designs created by Deepika</p>
</div>

<!-- Image Grid -->
<div class="container">
  <div class="row g-4">
    <!-- Repeat this block for each shot -->
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="shot-card">
        <img src="C:\web project\dibble1.jpg" alt="Shot 1">
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="shot-card">
        <img src="C:\web project\dibble2.jpg" alt="Shot 2">
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="shot-card">
        <img src="C:\web project\dibble3.jpg" alt="Shot 3">
      </div>
    </div>
    <div class="col-sm-6 col-md-4 col-lg-3">
      <div class="shot-card">
        <img src="C:\web project\dibble4.jpg" alt="Shot 4">
      </div>
    </div>
    <!-- Add more shots as needed -->
  </div>
</div>

<!-- Footer -->
<footer>
  <div class="container">
    <p class="mb-0">&copy; 2025 Created by Deepika S</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/00904d31-2e49-4f26-b09a-1a1989c7234f)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
