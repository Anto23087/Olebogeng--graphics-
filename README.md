<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Olebogeng Graphic's</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial Black', sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background: #000;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    header h1 {
      font-size: 28px;
      color: #fff;
      margin: 10px 0;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    nav a {
      color: #fff;
      margin: 10px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('graffiti-bg.jpg') no-repeat center center/cover;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 {
      font-size: 36px;
      color: #f00;
      margin-bottom: 10px;
    }
    .hero button {
      padding: 10px 20px;
      font-size: 18px;
      background: #ff0;
      color: #000;
      border: none;
      cursor: pointer;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
    }
    .services, .portfolio {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .service, .portfolio-item {
      background: #222;
      margin: 10px;
      padding: 20px;
      border-radius: 10px;
      width: 90%;
      max-width: 400px;
    }
    .service h3, .portfolio-item h3 {
      color: #ff0;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      color: #fff;
    }
    .contact-info {
      margin-top: 20px;
    }
    @media (min-width: 768px) {
      header {
        flex-direction: row;
        justify-content: space-between;
      }
      .services, .portfolio {
        flex-direction: row;
        justify-content: space-around;
        flex-wrap: wrap;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Olebogeng Graphic's</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Get a Custom Logo Today</h2>
    <p>Only the best.</p>
    <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Contact Now</button>
  </div>

  <section id="services">
    <h2 style="color:#f00; text-align:center">Services</h2>
    <div class="services">
      <div class="service">
        <h3>Logo Design</h3>
        <p>Unique and professional logos tailored to your brand.</p>
      </div>
      <div class="service">
        <h3>Branding Services</h3>
        <p>Comprehensive branding solutions for your business.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2 style="color:#f00; text-align:center">Portfolio</h2>
    <div class="portfolio">
      <div class="portfolio-item">
        <h3>Brand</h3>
        <img src="brand-sample.jpg" alt="Brand Sample" style="width:100%; border-radius: 5px;">
      </div>
      <div class="portfolio-item">
        <h3>Astra</h3>
        <img src="astra-sample.jpg" alt="Astra Sample" style="width:100%; border-radius: 5px;">
      </div>
    </div>
  </section>

  <section id="contact">
    <h2 style="color:#f00; text-align:center">Contact</h2>
    <div class="contact-info" style="text-align:center">
      <p><strong>WhatsApp:</strong> 072 450 7288</p>
      <p><strong>Email:</strong> <a href="mailto:olebogengkgakgane3@gmail.com" style="color:yellow">olebogengkgakgane3@gmail.com</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Olebogeng Graphic's | Only the best.</p>
  </footer>
</body>
</html>
