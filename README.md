
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YOUR BUSINESS NAME | Professional Welding</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <div class="logo">YOUR <span>BUSINESS</span></div>
    <div class="contact-info">
      <span class="phone">📞 (555) 123-4567</span>
      <nav>
        <a href="#services">Services</a>
        <a href="#gallery">Our Work</a>
        <a href="#contact" class="btn">Get a Quote</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Precision Welding & Metal Fabrication</h1>
      <p>Heavy duty structural welding, custom fabrication, and emergency repair services.</p>
      <a href="tel:5551234567" class="btn">Call: (555) 123-4567</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="card">
        <h3>Structural Welding</h3>
        <p>Reliable MIG, TIG, and Stick welding for heavy steel beams and construction projects.</p>
      </div>
      <div class="card">
        <h3>Custom Fabrication</h3>
        <p>Tailored metal gates, railings, brackets, and machinery built exactly to your blueprints.</p>
      </div>
      <div class="card">
        <h3>Mobile Repair</h3>
        <p>On-site emergency welding repairs for heavy equipment, trucks, and trailers.</p>
      </div>
    </div>
  </section>

  <!-- Project Gallery Section -->
  <section id="gallery" class="gallery-section">
    <h2>Our Recent Work</h2>
    <div class="gallery-grid">
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="Welding sparks">
        <div class="gallery-desc">Custom Gate Fabrication</div>
      </div>
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="Industrial steel fabrication">
        <div class="gallery-desc">Structural Steel Framing</div>
      </div>
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="On-site repair">
        <div class="gallery-desc">Mobile Equipment Repair</div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Request a Free Estimate</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Describe your welding project..." rows="5" required></textarea>
      <button type="submit" class="btn">Submit Request</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 YOUR BUSINESS NAME. All rights reserved.</p>
  </footer>

</body>
</html>
Use code with caution.
2. style.css (Updated with Gallery Layout)
Add these extra styles to your style.css file to format the gallery grid:
css
/* General Setup */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', Arial, sans-serif;
}

body {
  background-color: #1e1e24; /* Dark steel grey */
  color: #ffffff;
  line-height: 1.6;
}

/* Reusable Button Accent */
.btn {
  background-color: #ff6600; /* Hazard Orange */
  color: #1e1e24;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background-color: #e05500;
}

/* Header & Nav */
header {
  background-color: #111115;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 5%;
  border-bottom: 3px solid #ff6600;
  flex-wrap: wrap;
  gap: 15px;
}

.logo {
  font-size: 24px;
  font-weight: 900;
  letter-spacing: 1px;
}

.logo span {
  color: #ff6600;
}

.contact-info {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}

.phone {
  font-weight: bold;
  color: #ff6600;
}

nav a {
  color: #ffffff;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 500;
}

/* Hero Section */
.hero {
  padding: 100px 5%;
  text-align: center;
  background: linear-gradient(rgba(30,30,37,0.85), rgba(30,30,37,0.95)), url('https://unsplash.com') no-repeat center/cover;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
  color: #cccccc;
}

/* Services */
.services {
  padding: 60px 5%;
  background-color: #282830;
}

.services h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 32px;
}

.service-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  background-color: #1e1e24;
  padding: 30px;
  border-radius: 6px;
  width: 300px;
  border-left: 5px solid #ff6600;
}

.card h3 {
  margin-bottom: 15px;
}

/* New Gallery Section Layout */
.gallery-section {
  padding: 60px 5%;
  background-color: #1e1e24;
}

.gallery-section h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 32px;
}

.gallery-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.gallery-item {
  background-color: #111115;
  border-radius: 6px;
  overflow: hidden;
  width: 300px;
  border: 1px solid #333;
}

.gallery-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.gallery-desc {
  padding: 15px;
  text-align: center;
  font-weight: bold;
}

/* Contact Form */
.contact {
  padding: 60px 5%;
  max-width: 600px;
  margin: 0 auto;
}

.contact h2 {
  text-align: center;
  margin-bottom: 30px;
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

input, textarea {
  padding: 12px;
  border-radius: 4px;
  border: 1px solid #444;
  background-color: #111115;
  color: #fff;
  font-size: 16px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background-color: #111115;
  font-size: 14px;
  color: #777;
}
Use code with caution.
To complete this page, what are the exact business name and phone number you want to put in? I can drop them right into the code for you.




Here is your complete code, fully customized for Alfa Welder with your phone number 08029748401. The phone buttons are fully clickable, so customers on mobile devices can tap them to call you instantly.
The Final Code
1. index.html
Copy and paste this text directly into your HTML panel in CodePen or your local text editor:
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alfa Welder | Professional Welding & Fabrication</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <div class="logo">ALFA <span>WELDER</span></div>
    <div class="contact-info">
      <span class="phone">📞 08029748401</span>
      <nav>
        <a href="#services">Services</a>
        <a href="#gallery">Our Work</a>
        <a href="tel:08029748401" class="btn">Call Now</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Precision Welding & Metal Fabrication</h1>
      <p>Heavy duty structural welding, custom fabrication, and emergency repair services.</p>
      <a href="tel:08029748401" class="btn">Call: 08029748401</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="card">
        <h3>Structural Welding</h3>
        <p>Reliable MIG, TIG, and Stick welding for heavy steel beams and construction projects.</p>
      </div>
      <div class="card">
        <h3>Custom Fabrication</h3>
        <p>Tailored metal gates, railings, brackets, and machinery built exactly to your blueprints.</p>
      </div>
      <div class="card">
        <h3>Mobile Repair</h3>
        <p>On-site emergency welding repairs for heavy equipment, trucks, and trailers.</p>
      </div>
    </div>
  </section>

  <!-- Project Gallery Section -->
  <section id="gallery" class="gallery-section">
    <h2>Our Recent Work</h2>
    <div class="gallery-grid">
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="Welding sparks">
        <div class="gallery-desc">Custom Gate Fabrication</div>
      </div>
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="Industrial steel fabrication">
        <div class="gallery-desc">Structural Steel Framing</div>
      </div>
      <div class="gallery-item">
        <img src="https://unsplash.com" alt="On-site repair">
        <div class="gallery-desc">Mobile Equipment Repair</div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Request a Free Estimate</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Describe your welding project..." rows="5" required></textarea>
      <button type="submit" class="btn">Submit Request</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Alfa Welder. All rights reserved.</p>
  </footer>

</body>
</html>
Use code with caution.
2. style.css
Copy and paste this into your CSS file to link all the design structures together:
css
/* General Setup */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', Arial, sans-serif;
}

body {
  background-color: #1e1e24; 
  color: #ffffff;
  line-height: 1.6;
}

/* Reusable Button Accent */
.btn {
  background-color: #ff6600; /* Hazard Orange */
  color: #1e1e24;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 4px;
  border: none;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background-color: #e05500;
}

/* Header & Nav */
header {
  background-color: #111115;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 5%;
  border-bottom: 3px solid #ff6600;
  flex-wrap: wrap;
  gap: 15px;
}

.logo {
  font-size: 24px;
  font-weight: 900;
  letter-spacing: 1px;
}

.logo span {
  color: #ff6600;
}

.contact-info {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}

.phone {
  font-weight: bold;
  color: #ff6600;
}

nav a {
  color: #ffffff;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 500;
}

/* Hero Section */
.hero {
  padding: 100px 5%;
  text-align: center;
  background: linear-gradient(rgba(30,30,37,0.85), rgba(30,30,37,0.95)), url('https://unsplash.com') no-repeat center/cover;
}

.hero h1 {
  font-size: 42px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
  color: #cccccc;
}

/* Services */
.services {
  padding: 60px 5%;
  background-color: #282830;
}

.services h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 32px;
}

.service-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  background-color: #1e1e24;
  padding: 30px;
  border-radius: 6px;
  width: 300px;
  border-left: 5px solid #ff6600;
}

.card h3 {
  margin-bottom: 15px;
}

/* Gallery Section Layout */
.gallery-section {
  padding: 60px 5%;
  background-color: #1e1e24;
}

.gallery-section h2 {
  text-align: center;
  margin-bottom: 40px;
  font-size: 32px;
}

.gallery-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.gallery-item {
  background-color: #111115;
  border-radius: 6px;
  overflow: hidden;
  width: 300px;
  border: 1px solid #333;
}

.gallery-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.gallery-desc {
  padding: 15px;
  text-align: center;
  font-weight: bold;
}

/* Contact Form */
.contact {
  padding: 60px 5%;
  max-width: 600px;
  margin: 0 auto;
}

.contact h2 {
  text-align: center;
  margin-bottom: 30px;
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

input, textarea {
  padding: 12px;
  border-radius: 4px;
  border: 1px solid #444;
  background-color: #111115;
  color: #fff;
  font-size: 16px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background-color: #111115;
  font-size: 14px;
  color: #777;
}
