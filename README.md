# Project Responsive Web Design using Bootstrap
## Date:23/12/2024

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow">
        <div class="container">
            <a class="navbar-brand" href="#">Dribble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-light text-dark text-center py-5">
        <div class="container">
            <h1>Dribble</h1>
            <p class="lead">Showcase and discover exceptional design projects.</p>
            <a href="#About Us" class="btn btn-primary btn-lg">View Portfolio</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-5">
        <div class="container text-center">
            <h2 class="mb-4">Our Services</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">Design Showcase</h5>
                            <p class="card-text">Feature your best designs for the world to see.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">Collaboration</h5>
                            <p class="card-text">Work with other designers and grow together.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">Inspiration</h5>
                            <p class="card-text">Explore designs from a global community.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-5 bg-light">
        <div class="container text-center">
            <h2 class="mb-4">Portfolio</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="vietnam1.jpg" class="img-fluid rounded shadow-sm" alt="Portfolio Item">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="picture1.jpg" class="img-fluid rounded shadow-sm" alt="Portfolio Item">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="image-350x200 (6).jpg" class="img-fluid rounded shadow-sm" alt="Portfolio Item">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-light text-dark text-center py-3">
        <div class="container">
            <p><h3>Designed and Developed by Manasa devi AT</h3></p>
        </div>
    </footer>

    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


```
## OUTPUT:
![Screenshot (89)](https://github.com/user-attachments/assets/0a6db280-0d7b-4adb-a8e7-b7b445b9b864)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.

