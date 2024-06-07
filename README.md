# yoo
yoo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elly Decors</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Elly Decors</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Welcome to Elly Decors</h2>
        <p>Your one-stop destination for exquisite interior design products and services.</p>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Elly Decors is a premier destination for interior design enthusiasts, offering a wide range of products and services to transform your space into a masterpiece.</p>
    </section>
    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Living Room Furniture Set</h3>
            <p>Transform your living room with our elegant furniture set.</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Bedroom Decor Collection</h3>
            <p>Create a cozy sanctuary with our stylish bedroom decor collection.</p>
            <button>Add to Cart</button>
        </div>
        <!-- Add more products as needed -->
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or inquiries, feel free to contact us:</p>
        <p>Email: info@ellydecors.com</p>
        <p>Phone: +123456789</p>
    </section>
    <footer>
        <p>&copy; 2024 Elly Decors. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
}

.logo h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 50px 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

.product {
    margin-bottom: 40px;
}

.product img {
    max-width: 100%;
}

.product h3 {
    margin-top: 10px;
}

.product p {
    margin: 10px 0;
}

button {
    background-color: #333;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#history">History</a></li>
                <li><a href="#interior">Interior Designs</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="section">
        <h2>Welcome to My Website</h2>
        <p>This is the homepage of my website. Feel free to explore!</p>
    </section>
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>This section provides information about our company and what we do.</p>
    </section>
    <section id="history" class="section">
        <h2>Our History</h2>
        <p>Learn about our journey and how we became who we are today.</p>
    </section>
    <section id="interior" class="section">
        <h2>Interior Designs</h2>
        <p>Explore our stunning interior design projects and get inspired.</p>
    </section>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
}

.logo img {
    height: 50px; /* Adjust height as needed */
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.section {
    padding: 50px 20px;
    background-color: #fff;
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}
