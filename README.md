# Project Responsive Web Design using Bootstrap
## Date: 16/11/24

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
## HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Designs</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"> <!-- For icons -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Edu+AU+VIC+WA+NT+Pre:wght@400..700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css"> <!-- Custom CSS -->
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar">
    <div class="container">
      <a href="#" class="logo">Dribbble</a>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </div>
  </nav>
  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to Your Design World</h1>
      <p>Empower your business with the best digital solutions.</p>
      <a href="#services" class="btn">Explore Now</a>
    </div>
  </section>
  <!-- Services Section -->
  <section id="services" class="services">
    <div class="container">
      <h2 class="section-title">Our Services</h2>
      <div class="service-cards">
        <div class="card">
          <i class="fas fa-laptop-code"></i>
          <h3>Web Development</h3>
          <p>Custom websites and web applications designed to boost your business.</p>
        </div>
        <div class="card">
          <i class="fas fa-search"></i>
          <h3>SEO Optimization</h3>
          <p>Increase your visibility and drive more traffic to your site.</p>
        </div>
        <div class="card">
          <i class="fas fa-chart-line"></i>
          <h3>Marketing Strategy</h3>
          <p>Tailored marketing strategies to help you grow your business.</p>
        </div>
      </div>
    </div>
  </section>
  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2024 Your Brand. All Rights Reserved.</p>
    </div>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
  <script src="script.js"></script>
</body>
</html>

```
## CSS:
```
/* Basic reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body and Font */
body {
  font-family: "Edu AU VIC WA NT Pre", cursive;
  line-height: 1.6;
}

/* Navbar */
.navbar {
  background: #277586;
  color: #fff;
  padding: 10px 0;
  position: sticky;
  top: 0;
  z-index: 1000;
}
.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}
.navbar .logo {
  font-size: 24px;
  font-weight: bold;
  color: #fff;
  text-decoration: none;
}
.navbar .nav-links {
  list-style: none;
  display: flex;
}
.navbar .nav-links li {
  margin-left: 20px;
}
.navbar .nav-links a {
  color: #fff;
  text-decoration: none;
  font-size: 16px;
  transition: color 0.3s;
}
.navbar .nav-links a:hover {
  color: #f4f4f4;
}

/* Hero Section */
.hero {
  background: url('https://picsum.photos/2000/800') no-repeat center center/cover;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  text-align: center;
}
.hero-content h1 {
  font-size: 50px;
  font-weight: bold;
}
.hero-content p {
  font-size: 18px;
  margin: 20px 0;
}
.hero .btn {
  background: #ff5733;
  color: #fff;
  padding: 15px 30px;
  border-radius: 25px;
  font-size: 18px;
  text-decoration: none;
  transition: background 0.3s;
}
.hero .btn:hover {
  background: #e04e29;
}

/* Services Section */
.services {
  padding: 50px 0;
  background: #f9f9f9;
}
.services .section-title {
  text-align: center;
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 40px;
}
.services .service-cards {
  display: flex;
  justify-content: space-between;
  max-width: 1200px;
  margin: 0 auto;
  flex-wrap: wrap;
}
.services .card {
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  padding: 30px;
  text-align: center;
  width: 30%;
  margin-bottom: 30px;
  transition: transform 0.3s ease-in-out;
}
.services .card:hover {
  transform: translateY(-10px);
}
.services .card i {
  font-size: 40px;
  color: #ff5733;
  margin-bottom: 20px;
}
.services .card h3 {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 15px;
}
.services .card p {
  font-size: 16px;
  color: #555;
}

/* Footer */
footer {
  background: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}
footer p {
  font-size: 14px;
}

```

## OUTPUT:
![Screenshot 2024-11-16 105420](https://github.com/user-attachments/assets/42e64473-7e3f-463d-9199-d809df8e24ef)
![Screenshot 2024-11-16 105436](https://github.com/user-attachments/assets/5446faa7-0ab2-4f71-9760-d28e728462db)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
