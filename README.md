# MK-Milk
Dairy milk supply 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mill Dairy Supply - Fresh Dairy Delivered</title>
  <style>
    * {
      margin: 0; padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
    }
    body {
      background: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #2c3e50;
      padding: 20px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: white;
    }
    header h1 {
      font-size: 28px;
    }
    nav a {
      color: #ffffff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1585238341986-2f58b3c224e5') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h2 {
      font-size: 48px;
      text-shadow: 2px 2px 5px #000;
    }
    .hero p {
      font-size: 20px;
      margin-top: 10px;
      text-shadow: 1px 1px 4px #000;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      background: #27ae60;
      color: white;
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      text-align: center;
    }
    .section-title {
      font-size: 32px;
      margin-bottom: 20px;
      color: #2c3e50;
    }
    .about p {
      max-width: 700px;
      margin: auto;
      font-size: 18px;
      line-height: 1.6;
    }
    .services, .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .service-card, .product {
      background: white;
      padding: 20px;
      width: 260px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .service-card img, .product img {
      width: 100%;
      border-radius: 10px;
    }
    .service-card h4, .product p {
      margin-top: 10px;
      color: #27ae60;
    }
    footer {
      background: #2c3e50;
      color: #ccc;
      padding: 30px 20px;
      text-align: center;
    }
    footer a {
      color: #ccc;
      margin: 0 10px;
      text-decoration: none;
      font-size: 14px;
    }
    footer a:hover {
      color: #fff;
    }
    .policy {
      max-width: 800px;
      margin: auto;
      text-align: left;
      font-size: 15px;
      line-height: 1.6;
    }

    @media (max-width: 768px) {
      header, nav {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }
      .services, .products {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Mill Dairy Supply</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
      <a href="#policies">Policies</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Pure. Fresh. Daily.</h2>
    <p>We Deliver Farm-Fresh Dairy Products To Your Doorstep</p>
    <a href="#contact" class="btn">Get Started</a>
  </section>

  <!-- About -->
  <section id="about" class="about">
    <h3 class="section-title">About Us</h3>
    <p>Mill Dairy Supply is a trusted name in delivering hygienic and fresh dairy products. We source directly from farms, ensuring purity and quality. Join thousands of happy customers who rely on us for their daily milk, curd, paneer, and more!</p>
  </section>

  <!-- Services -->
  <section id="services">
    <h3 class="section-title">Our Services</h3>
    <div class="services">
      <div class="service-card">
        <img src="https://cdn-icons-png.flaticon.com/512/6513/6513983.png" alt="Milk Delivery">
        <h4>Daily Milk Delivery</h4>
        <p>Morning milk supply to your home every day.</p>
      </div>
      <div class="service-card">
        <img src="https://cdn-icons-png.flaticon.com/512/2933/2933802.png" alt="Bulk Supply">
        <h4>Bulk Supply</h4>
        <p>Supplying milk & paneer to restaurants & shops.</p>
      </div>
      <div class="service-card">
        <img src="https://cdn-icons-png.flaticon.com/512/1355/1355230.png" alt="Curd Paneer">
        <h4>Curd & Paneer</h4>
        <p>Home-style thick curd and soft paneer available.</p>
      </div>
    </div>
  </section>

  <!-- Products -->
  <section id="products">
    <h3 class="section-title">Our Products</h3>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587" alt="Milk">
        <p>Farm Fresh Cow Milk</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1624378449549-14f88cefd75e" alt="Paneer">
        <p>Soft White Paneer</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1624378832732-43e2153c9b13" alt="Curd">
        <p>Thick Homemade Curd</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h3 class="section-title">Contact Us</h3>
    <form style="max-width: 600px; margin:auto; text-align: left;">
      <label>Your Name:</label>
      <input type="text" placeholder="Enter name" style="width:100%; padding:10px; margin-bottom:10px;" required>
      
      <label>Email:</label>
      <input type="email" placeholder="Enter email" style="width:100%; padding:10px; margin-bottom:10px;" required>
      
      <label>Message:</label>
      <textarea rows="4" placeholder="Write your message" style="width:100%; padding:10px;"></textarea>
      
      <button type="submit" style="margin-top:10px; padding:10px 20px; background:#27ae60; color:#fff; border:none; border-radius:5px;">Send</button>
    </form>
  </section>

  <!-- Policies Section -->
  <section id="policies">
    <h3 class="section-title">Our Policies</h3>
    <div class="policy">
      <h4>Terms & Conditions</h4>
      <p>By using our services, you agree to comply with all our rules and guidelines. We deliver products based on your selected subscription or order terms.</p>

      <h4>Privacy Policy</h4>
      <p>Your data is safe with us. We do not share your personal information with third parties without your consent.</p>

      <h4>Refund Policy</h4>
      <p>If delivery is missed or product quality is not satisfactory, refunds or replacements can be requested within 24 hours.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>
      <a href="#policies">Terms & Conditions</a> |
      <a href="#policies">Privacy Policy</a> |
      <a href="#policies">Refund Policy</a> |
      <a href="#contact">Contact Us</a> |
      <a href="#about">About Us</a>
    </p>
    <p>&copy; 2025 Mill Dairy Supply. All Rights Reserved.</p>
  </footer>

</body>
</html>
