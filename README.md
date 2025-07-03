<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lizpaz Sound System</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      padding: 1em;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #ffcc00;
    }
    nav {
      background-color: #333;
      text-align: center;
      padding: 0.5em;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2em;
    }
    .product {
      background-color: #222;
      border: 1px solid #444;
      border-radius: 8px;
      margin: 1em;
      padding: 1em;
      width: 250px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .product h2 {
      color: #ffcc00;
      font-size: 1.2em;
    }
    .product p {
      font-size: 0.9em;
    }
    footer {
      background-color: #222;
      text-align: center;
      padding: 1em;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lizpaz Sound System</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="products" id="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Speaker">
      <h2>Portable Speaker</h2>
      <p>High-quality Bluetooth speaker, ideal for events.</p>
      <p><strong>Ksh 5,000</strong></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Microphone">
      <h2>Wireless Microphone</h2>
      <p>Clear sound with long-range coverage.</p>
      <p><strong>Ksh 3,500</strong></p>
    </div>
    <!-- Add more products as needed -->
  </section>

  <footer id="contact">
    <p>Contact us: lizpazsounds@example.com | +254 700 123 456</p>
    <p>&copy; 2025 Lizpaz Sound System</p>
  </footer>
</body>
</html>
