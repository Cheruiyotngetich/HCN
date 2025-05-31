<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Howard Urban Clothing</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: white;
      color: black;
    }
    header {
      background-color: black;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: green;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
    }
    nav a:hover {
      background-color: red;
    }
    .section {
      padding: 2rem;
    }
    h2 {
      border-bottom: 2px solid green;
      padding-bottom: 0.5rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
    }
    .product {
      border: 1px solid #ccc;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .btn {
      background-color: green;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      margin-top: 0.5rem;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
    }
    .btn:hover {
      background-color: red;
    }
    footer {
      text-align: center;
      background-color: black;
      color: white;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Howard Urban Clothing</h1>
    <p>Stylish clothing for Men and Women</p>
  </header>
  <nav>
    <a href="#men">Men</a>
    <a href="#ladies">Ladies</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="section" id="men">
    <h2>Men's Clothing</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Official+Shirt" alt="Official Shirt">
        <h3>Official Shirt</h3>
        <p>Ksh 850</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Official%20Shirt">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Polo+T-shirt" alt="Polo T-shirt">
        <h3>Polo T-shirt</h3>
        <p>Ksh 730</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Polo%20T-shirt">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Denim+Jeans" alt="Denim Jeans">
        <h3>Denim Jeans Trousers</h3>
        <p>Ksh 1350</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Denim%20Jeans">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Khaki+Trousers" alt="Soft Khaki Trousers">
        <h3>Soft Khaki Trousers</h3>
        <p>Ksh 1400</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Soft%20Khaki%20Trousers">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Jacket" alt="Jacket">
        <h3>Jacket</h3>
        <p>Ksh 1900</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Jacket">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Shirt" alt="Shirt">
        <h3>Shirt</h3>
        <p>Ksh 1200</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Shirt">Buy on WhatsApp</a>
      </div>
    </div>
  </section>

  <section class="section" id="ladies">
    <h2>Ladies' Clothing</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Denim+Jeans" alt="Denim Jeans">
        <h3>Denim Jeans Trousers</h3>
        <p>Ksh 1350</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Ladies%20Denim%20Jeans">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Khaki+Trousers" alt="Soft Khaki Trousers">
        <h3>Soft Khaki Trousers</h3>
        <p>Ksh 1400</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Ladies%20Soft%20Khaki%20Trousers">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Shirt" alt="Shirt">
        <h3>Shirt</h3>
        <p>Ksh 1200</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Ladies%20Shirt">Buy on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Jacket" alt="Jacket">
        <h3>Jacket</h3>
        <p>Ksh 1900</p>
        <a class="btn" href="https://wa.me/1234567890?text=I'm%20interested%20in%20the%20Ladies%20Jacket">Buy on WhatsApp</a>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Have a question? Message us directly on WhatsApp!</p>
    <a class="btn" href="https://wa.me/1234567890">Chat on WhatsApp</a>
  </section>

  <footer>
    <p>&copy; 2025 Howard Urban Clothing. All rights reserved.</p>
  </footer>
</body>
</html>
