<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comedic Stickers Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Comedic Stickers</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero">
            <h2>Welcome to the Funniest Sticker Store!</h2>
            <p>Find unique stickers inspired by celebrities to brighten your day.</p>
            <a href="#products" class="cta">Shop Now</a>
        </section>

        <section id="products" class="products">
            <h2>Our Products</h2>
            <div class="product-list">
                <div class="product-item">
                    <img src="sticker1.jpg" alt="Celebrity Sticker 1">
                    <h3>Celebrity Sticker 1</h3>
                    <p>$5.00</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product-item">
                    <img src="sticker2.jpg" alt="Celebrity Sticker 2">
                    <h3>Celebrity Sticker 2</h3>
                    <p>$5.00</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </section>

        <section id="about" class="about">
            <h2>About Us</h2>
            <p>We create high-quality, hilarious stickers inspired by your favorite celebrities. Perfect for personalizing your gadgets, notebooks, and more!</p>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send</button>
            </form>
        </section>

        <section id="payment" class="payment">
            <h2>Payment Information</h2>
            <p>We currently offer <strong>Cash on Delivery</strong>. Place your order and pay when your package arrives at your doorstep!</p>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Comedic Stickers Store. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
