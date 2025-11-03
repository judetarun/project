# Project Responsive Web Design using Bootstrap
# Date:1.11.2025
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
project.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Showcase</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .portfolio-img {
            width: 100%;
            height: 300px; 
            object-fit: cover;
        }
        footer {
            background-color: #ececec;
            padding: 30px 0;
            text-align: center;
        }
        .card-body p {
            font-size: 0.9rem;
        }
        .btn-custom {
            background-color: #007bff;
            color: white;
        }
        .btn-custom:hover {
            background-color: #0056b3;
        }
        .navbar-brand {
            font-weight: bold;
        }
        
        .btn-light{
            color: #000000;
            background-color: #84a3c4;
        }
       
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Creative Showcase</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Our Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Creative Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Get in Touch</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-custom" href="signup.html">Join Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="bg-dark text-white text-center py-6">
        <div class="container">
            <h1>Unleash Your Creative Potential</h1>
            <p class="lead">A place for designers to showcase their work and be inspired by others.</p>
            <a href="#portfolio" class="btn btn-light btn-lg">Explore Works</a>
        </div>
    </header>

    <section id="features" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Services</h2>
            <div class="row text-center">
                <div class="col-md-4 mb-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">For Designers</h5>
                            <p class="card-text">Create a personal portfolio and enhance your online presence. Showcase your work to a wider audience.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">For Inspiration</h5>
                            <p class="card-text">Discover amazing designs and creative ideas from designers around the world. Get inspired and create your own.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card shadow">
                        <div class="card-body">
                            <h5 class="card-title">For Businesses</h5>
                            <p class="card-text">Collaborate with talented designers to bring your business vision to life. Find top-notch creatives here.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="portfolio" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">Creative Portfolio</h2>
            <p class="text-center mb-4">Browse through some of the best creative works shared by our global community of designers.</p>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="BRAND.jpg" class="portfolio-img" alt="Retrospective Branding">
                        <div class="card-body">
                            <h5 class="card-title">Retro Branding Design</h5>
                            <p class="card-text">A fusion of classic and modern design elements, inspired by retro branding trends.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="home.jpg" class="portfolio-img" alt="Home Swap UI">
                        <div class="card-body">
                            <h5 class="card-title">Home Swap UI Elements</h5>
                            <p class="card-text">Clean and intuitive UI design for a home swapping platform, built for simplicity and ease of use.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="jewel.jpg" class="portfolio-img" alt="Jewelry E-Commerce">
                        <div class="card-body">
                            <h5 class="card-title">Jewelry E-Commerce Design</h5>
                            <p class="card-text">A luxurious online store design for a jewelry brand, focused on aesthetics and user engagement.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="EV.jpg" class="portfolio-img" alt="EV Station Branding">
                        <div class="card-body">
                            <h5 class="card-title">EV Charging Station Branding</h5>
                            <p class="card-text">Eco-friendly branding for electric vehicle charging stations, reflecting sustainability and modern design.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="fitness.jpg" class="portfolio-img" alt="Fitness App Design">
                        <div class="card-body">
                            <h5 class="card-title">Fitness App Interface</h5>
                            <p class="card-text">A sleek mobile app UI design for tracking fitness progress, focusing on usability and functionality.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="coffee.jpg" class="portfolio-img" alt="Coffee Shop Logo">
                        <div class="card-body">
                            <h5 class="card-title">Coffee Shop Branding</h5>
                            <p class="card-text">A cozy and minimalist logo for a local coffee shop, capturing warmth and comfort in design.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Get in Touch</h2>
            <p class="text-center mb-4">We’d love to hear from you! If you have any inquiries, feedback, or suggestions, feel free to reach out.</p>
            <form action="#" method="POST">
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" name="name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>
                <div class="mb-3">
                    <label for="subject" class="form-label">Subject</label>
                    <input type="text" class="form-control" id="subject" name="subject" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-custom w-100">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Creative Showcase.JUDE TARUN 212224040144 All Rights Reserved.</p>
    </footer>
</body>
</html>
```
signup.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .container {
            max-width: 500px;
        }
        .form-container {
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: #faffd5;
        }
    </style>
</head>
<body>
    <div class="container mt-5">
        <div class="form-container">
            <h2 class="text-center mb-4">Create an Account</h2>
            <form action="#" method="POST">
                <div class="mb-3">
                    <label for="fullName" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="fullName" name="fullName" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" name="password" required>
                </div>
                <div class="mb-3">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" name="confirmPassword" required>
                </div>
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="terms" required>
                    <label class="form-check-label" for="terms">I agree to the terms and conditions</label>
                </div>
                <button type="submit" class="btn btn-primary w-100">Sign Up</button>
            </form>
            <p class="text-center mt-3">Already have an account? <a href="login.html">Login here</a></p>
        </div>
    </div>
</body>
</html>
```
# OUTPUT:
![alt text](<tarun/proj/Screenshot 2025-05-12 110018.png>)
![alt text](<tarun/proj/Screenshot 2025-05-12 110027.png>)
![alt text](<tarun/proj/Screenshot 2025-05-12 110041.png>)
![alt text](<tarun/proj/Screenshot 2025-05-12 110050.png>)
# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
