<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
  <title>Sweetshopniferdi</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-image: url('bgkonato.jpg'); /* Replace 'overall-background.jpg' with your image file */
      background-size: cover;
      background-position: center;
      color: white;
    }

    header {
      background-color: rgba(0, 0, 0, 0.5);
      text-align: center;
      padding: 1.5em 0;
    }

    .logo {
      font-size: 2.5em;
      font-weight: bold;
      letter-spacing: 2px;
      color: #4CAF50;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
      margin-bottom: 10px;
    }

    .slogan {
      font-size: 1.2em;
      color: #ddd;
    }

    .search-bar {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 15px;
    }

    input[type="text"] {
      padding: 10px;
      border-radius: 8px;
      border: none;
      width: calc(70% - 20px);
      margin-bottom: 10px;
      font-size: 1em;
    }

    .search-btn {
      background-color: #4CAF50;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1em;
      transition: background-color 0.3s ease;
    }

    .search-btn:hover {
      background-color: #45a049;
    }

    nav {
      background-color: transparent;
      padding: 1em 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      padding: 15px 20px;
      margin: 0 10px;
      border-radius: 8px;
      transition: background-color 0.3s ease;
    }

    nav a:hover {
      background-color: rgba(255, 255, 255, 0.2);
    }

    .nav-links {
      display: flex;
    }

    section {
      padding: 15px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .product {
      position: relative;
      border: none;
      overflow: hidden;
      border-radius: 10px;
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
      width: calc(45% - 20px);
      margin: 10px;
    }

    .product:hover {
      transform: translateY(-10px);
    }

    .product-content {
      position: relative;
      z-index: 1;
      padding: 15px;
      background-color: rgba(255, 255, 255, 0.9);
      border-radius: 0 0 10px 10px;
      transition: transform 0.3s ease;
    }

    .product img {
      width: 100%;
      border-radius: 10px 10px 0 0;
      object-fit: cover;
      height: 200px;
    }

    .product-details {
      z-index: 2;
    }

    .product h3 {
      color: #333;
      font-size: 1.8em;
      margin-bottom: 8px;
    }

    .product p {
      color: #666;
      font-size: 1.2em;
      margin-bottom: 10px;
    }

    .add-to-cart-btn {
      background-color: #4CAF50;
      color: white;
      padding: 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1.2em;
      transition: background-color 0.3s ease;
    }

    .add-to-cart-btn:hover {
      background-color: #45a049;
    }

    .footer-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .footer-text {
      width: 50%;
      text-align: left;
    }

    .owner-description {
      width: 50%;
      text-align: right;
      max-width: 500px; /* Adjust as needed */
    }

    .owner-image {
      width: 50%;
      max-width: 100px; /* Adjust as needed */
      border-radius: 50%;
      overflow: hidden;
    }

    .owner-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    footer {
      background-color: #333;
      color: white;
      padding: 1.5em 0;
      width: 100%;
    }

    @media only screen and (max-width: 768px) {
      .search-bar {
        flex-direction: column;
        align-items: stretch;
      }

      .search-btn {
        width: calc(70% - 20px);
        margin-top: 10px;
      }

      input[type="text"] {
        width: calc(70% - 20px);
      }

      .product {
        width: calc(100% - 20px);
      }

      .product img {
        height: 150px;
      }

      .product h3 {
        font-size: 1.5em;
      }

      .product p {
        font-size: 1em;
      }

      .add-to-cart-btn {
        padding: 10px;
        font-size: 1em;
      }

      nav a {
        color: #333; /* Adjust the text color for better visibility */
        margin: 0 5px;
      }

      .footer-content {
        flex-direction: column;
        text-align: center;
      }

      .owner-image {
        margin-top: 20px;
        width: 30%;
      }

      .owner-description {
        width: 70%;
        margin-top: 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">SWEET AND GREET</div>
    <div class="slogan">Mini Donuts & Waffles</div>
    <div class="search-bar">
      <input type="text" placeholder="Search...">
      <button class="search-btn">Search</button>
    </div>
  </header>

  <nav>
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Profile</a>
      <a href="#">Cart</a>
    </div>
  </nav>

  <section>
    <!-- Product cards go here -->
    <section>
  <div class="product">
    <img src="waffle.jpg" alt="Product 1 Image">
    <div class="product-content">
      <div class="product-details">
        <h3>Waffle</h3>
        <p>Unang kagat i love agad dahil bumili ka sana pumasa ka🙌🏻</p>
        <button class="add-to-cart-btn">Add to Cart</button>
      </div>
    </div>
  </div>

  <div class="product">
    <img src="minidonut.jpg" alt="Product 2 Image">
    <div class="product-content">
      <div class="product-details">
        <h3>Mini Donut</h3>
        <p>Ang pinaka da best sa lahat dahil kasing tamis ni kyle ang mini donut ko🤤</p>
        <button class="add-to-cart-btn">Add to Cart</button>
      </div>
    </div>
  </div>
  <!-- Add more product cards as needed -->
</section>

  </section>

  <footer>
    <div class="footer-content">
      <div class="footer-text">
        <h3 style="text-align:center;font-family: Courier">Ferdinand U Liscano</h3>
      </div>
      <div class="owner-image">
        <img src="ferdi.jpg" alt="Owner Image">
      </div>
      <div class="owner-description">
        <p style="text-align:center">Sabi ng mama ko wag daw basta basta maniwala sa mga babae🙂</p>
      </div>
    </div>
  </footer>
</body>
</html>
