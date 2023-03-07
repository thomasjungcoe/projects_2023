<!DOCTYPE html>
<html>
<head>
	<title>Welcome to Startup Company</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
	<link rel="stylesheet" href="style.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>
<body>
<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Startup Company</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#services">Services</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#contact">Contact</a>
      </li>
    </ul>
  </div>
</nav>

<!-- Banner -->
<div class="banner">
	<div class="container">
		<h1>Welcome to Startup Company</h1>
		<p>We help businesses grow through innovative solutions</p>
		<a href="#services" class="btn btn-primary btn-lg">Learn More</a>
	</div>
</div>

<!-- About Section -->
<section id="about">
	<div class="container">
		<div class="row">
			<div class="col-md-6">
				<img src="https://via.placeholder.com/500x300" alt="About Us Image" class="img-fluid">
			</div>
			<div class="col-md-6">
				<h2>About Us</h2>
				<p>Startup Company is a full-service digital agency that provides innovative solutions to help businesses grow. Our team of experts is passionate about creating custom strategies that meet the unique needs of our clients. Whether you need help with web design, SEO, or social media, we've got you covered.</p>
			</div>
		</div>
	</div>
</section>

<!-- Services Section -->
<section id="services">
	<div class="container">
		<h2>Our Services</h2>
		<div class="row">
			<div class="col-md-4">
				<div class="card">
				  <img src="https://via.placeholder.com/500x300" alt="Service 1 Image" class="card-img-top">
				  <div class="card-body">
				    <h5 class="card-title">Web Design</h5>
				    <p class="card-text">We create stunning, responsive websites that will impress your customers and help you stand out from the competition.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                  </div>
                </div>
            </div>
        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/500x300" alt="Service 2 Image" class="card-img-top">
                <div class="card-body">
                    <h5 class="card-title">Search Engine Optimization</h5>
                    <p class="card-text">We help you get found on Google and other search engines by optimizing your website for targeted keywords and increasing your online visibility.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card">
                <img src="https://via.placeholder.com/500x300" alt="Service 3 Image" class="card-img-top">
                <div class="card-body">
                    <h5 class="card-title">Social Media Marketing</h5>
                    <p class="card-text">We help you connect with your audience on social media platforms such as Facebook, Instagram, and Twitter by creating engaging content and targeted ads.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>  
                </div>
            </div>
        </div>
    </div>
</div>
</section>

<!-- Contact Section -->
<section id="contact">
	<div class="container">
		<h2>Contact Us</h2>
		<form>
		  <div class="form-group">
		    <label for="name">Name:</label>
		    <input type="text" class="form-control" id="name" placeholder="Enter your name">
		  </div>
		  <div class="form-group">
		    <label for="email">Email:</label>
		    <input type="email" class="form-control" id="email" placeholder="Enter your email">
		  </div>
		  <div class="form-group">
		    <label for="message">Message:</label>
		    <textarea class="form-control" id="message" rows="5"></textarea>
		  </div>
		  <button type="submit" class="btn btn-primary">Submit</button>
		</form>
	</div>
</section>

<!-- Footer -->
<footer>
	<div class="container">
		<p>&copy; 2023 Startup Company. All rights reserved.</p>
	</div>
</footer>

</body>
</html>
