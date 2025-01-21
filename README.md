<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bazario</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
        }
        nav a:hover {
            background-color: #555;
        }
        .hero {
            text-align: center;
            padding: 2rem;
            background: url('https://via.placeholder.com/1920x500') no-repeat center;
            background-size: cover;
            color: white;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
            padding: 2rem;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 8px;
            text-align: center;
            padding: 1rem;
            background-color: #f9f9f9;
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .product button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 0.5rem;
        }
        .product button:hover {
            background-color: #218838;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Bazario</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h2>Your Bazaar of Amazing Deals!</h2>
        <p>Explore unique finds and shop with ease.</p>
    </div>
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 2">
            <h3>Product 2</h3>
            <p>$20.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 3">
            <h3>Product 3</h3>
            <p>$15.00</p>
            <button>Add to Cart</button>
        </div>
    </section>
    <footer id="contact">
        <p>&copy; 2025 Bazario. All rights reserved.</p>
    </footer>
</body>
</html>
