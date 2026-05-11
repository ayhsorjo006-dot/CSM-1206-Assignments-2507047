<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pran.bd</title>
    <link rel="stylesheet" href="sh.css">
    <script src="SHOAIB.js"></script>
</head>

<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="pran.jpg" alt="Pran Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li class="dropdown">
                    <a href="#products">Products</a>
                    <div class="dropdown-content">
                        <a href="#juices">Juices</a>
                        <a href="#snacks">Snacks</a>
                        <a href="#dairy">Dairy</a>
                        <a href="#spices">Spices</a>
                    </div>
                </li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Welcome PRAN</h1>
            <p>Taste the Goodness</p>
            <a href="#products" class="btn">Explore Our Products</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="istockphoto-467416670-612x612.jpg"
                    alt="Juices">
                <h3>Juicy Bun</h3>
                <p>Refreshing and healthy fruit juices.</p>
            </div>
            <div class="product-card">
                <img src="ai-generated-snacks-in-a-container-professional-advertising-foodgraphy-photo.jpg"
                    alt="Snacks">
                <h3>Snacks</h3>
                <p>Delicious and crunchy snacks for every occasion.</p>
            </div>
            <div class="product-card">
                <img src=" images.jpeg"
                    alt="Dairy">
                <h3>Drinks</h3>
                <p>Pure and nutritious dairy products.</p>
            </div>
            <div class="product-card">
                <img src="images.webp" 
                   alt="Spices">
                <h3>Spices</h3>
                <p>Authentic spices to enhance your cooking.</p>
            </div>
        </div>
    </section>
    <!--calculator-->

    <div class="container">
        <section id="calculator" class="section">
            <h2>Calculate Your Calorie Intake</h2>
            <form id="calorie-form">
                <div class="form-group">
                    <label for="quantity1">Pran Juice (1mL) - 100 calories:</label>
                    <input type="number" id="quantity1" name="quantity1" min="0" value="0">
                </div>
                <div class="form-group">
                    <label for="quantity2">Pran Chips (1g) - 250 calories:</label>
                    <input type="number" id="quantity2" name="quantity2" min="0" value="0">
                </div>
                <div class="form-group">
                    <label for="quantity3">Pran Biscuits (1g) - 400 calories:</label>
                    <input type="number" id="quantity3" name="quantity3" min="0" value="0">
                </div>
                <button type="submit">Calculate</button>
            </form>
            <p id="totalCalories">Total Calories: 0</p>
        </section>
    </div>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Pran.bd is one of the leading food and beverage companies in Bangladesh. We are committed to providing
            high-quality, nutritious, and delicious products to our customers. Our mission is to bring the taste of
            Bangladesh to the world.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <h2> Call for any query</h2>
        <table class="table">
            <tr>
                <th>Office</th>
                <th>Number</th>
            </tr>
            <tr>
                <td>Bangladesh</td>
                <td>+586937865</td>
            </tr>
            <tr>
                <td>India</td>
                <td>04792874</td>
            </tr>
            <tr>
                <td>Singapore</td>
                <td>911244</td>
            </tr>         
        </table>
    </section>

    <!-- Footer Section -->
    <footer>
        <a href="https://www.facebook.com/" ><img src="facebook.png" height="50" width="50"></a>
        <a href="https://www.youtube.com/"><img src="twitter (1).png" height="50" width="50"></a>
        <a href="https://www.instagram.com/"><img src="instagram-logo.png" height="50" width="50"></a>
        <p>&copy; 2025 Pran.bd All rights reserved.</p>
    </footer>
</body>

</html>
