<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Buy Mart E Shop</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Best Buy Mart E Shop</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>Welcome to Best Buy Mart E Shop</h2>
            <p>Your one-stop shop for quality products at unbeatable prices!</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="products">
        <div class="container">
            <h2>Our Products</h2>
            <div class="product-grid">
                <div class="product">
                    <img src="assets/product1.jpg" alt="Product 1">
                    <h3>Product 1</h3>
                    <p>$10.00</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product">
                    <img src="assets/product2.jpg" alt="Product 2">
                    <h3>Product 2</h3>
                    <p>$15.00</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product">
                    <img src="assets/product3.jpg" alt="Product 3">
                    <h3>Product 3</h3>
                    <p>$20.00</p>
                    <button>Add to Cart</button>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Best Buy Mart E Shop is dedicated to providing top-quality products at affordable prices. We pride ourselves on excellent customer service and a seamless shopping experience.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Best Buy Mart E Shop. All Rights Reserved. | <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
        </div>
    </footer>
</body>
</html>
