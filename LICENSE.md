<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Marae Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #FF66B2; /* Pink */
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #000; /* Black */
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .product-item {
            background-color: #f1f1f1;
            margin: 10px;
            padding: 15px;
            width: 250px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product-item img {
            width: 100%;
            border-radius: 8px;
        }
        .product-item h3 {
            color: #FF66B2;
        }
        .contact {
            background-color: #FF66B2;
            padding: 20px;
            text-align: center;
            color: white;
        }
        footer {
            background-color: #000;
            color: white;
            padding: 10px;
            text-align: center;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Marae Store</h1>
        <p>Welcome to our cute and stylish online store!</p>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="products" class="product">
        <div class="product-item">
            <img src="https://via.placeholder.com/250x250" alt="Product 1">
            <h3>Product 1</h3>
            <p>$25.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-item">
            <img src="https://via.placeholder.com/250x250" alt="Product 2">
            <h3>Product 2</h3>
            <p>$30.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-item">
            <img src="https://via.placeholder.com/250x250" alt="Product 3">
            <h3>Product 3</h3>
            <p>$20.00</p>
            <button>Add to Cart</button>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have any questions? Reach out to us!</p>
        <form>
            <input type="text" placeholder="Your Name" required><br><br>
            <input type="email" placeholder="Your Email" required><br><br>
            <textarea placeholder="Your Message" required></textarea><br><br>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Marae Store | <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>
</body>
</html>
