<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apartment Listings</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Find Your Dream Apartment</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    
    <section class="apartment-listings">
        <div class="apartment">
            <a href="apartment1.html">
                <img src="apartment1.jpg" alt="Apartment 1">
                <h2>Luxury Apartment in the City Center</h2>
                <p>2 Beds, 2 Baths - $500,000</p>
            </a>
        </div>

        <div class="apartment">
            <a href="apartment2.html">
                <img src="apartment2.jpg" alt="Apartment 2">
                <h2>Modern Apartment with Sea View</h2>
                <p>3 Beds, 2 Baths - $750,000</p>
            </a>
        </div>

        <div class="apartment">
            <a href="apartment3.html">
                <img src="apartment3.jpg" alt="Apartment 3">
                <h2>Cozy Apartment in the Suburbs</h2>
                <p>1 Bed, 1 Bath - $300,000</p>
            </a>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2024 Apartment Listings. All Rights Reserved.</p>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #007bff;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

h1 {
    margin-bottom: 10px;
}

.apartment-listings {
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
    padding: 0 20px;
}

.apartment {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 30%;
    text-align: center;
    padding: 15px;
    transition: transform 0.3s ease;
}

.apartment img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.apartment h2 {
    margin-top: 15px;
    font-size: 18px;
}

.apartment p {
    color: #777;
    margin: 10px 0;
}

.apartment:hover {
    transform: scale(1.05);
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxury Apartment in the City Center</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Luxury Apartment in the City Center</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    
    <section class="apartment-detail">
        <img src="apartment1.jpg" alt="Apartment 1">
        <h2>2 Beds, 2 Baths - $500,000</h2>
        <p>This luxurious apartment is located in the heart of the city, offering stunning views and modern amenities. Perfect for those who want to experience city living at its finest.</p>
        <p>Features:</p>
        <ul>
            <li>Spacious living area</li>
            <li>Fully-equipped kitchen</li>
            <li>Balcony with city views</li>
            <li>24/7 security</li>
        </ul>
    </section>
    
    <footer>
        <p>&copy; 2024 Apartment Listings. All Rights Reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <a href="index.html">Home</a>
        </nav>
    </header>
    
    <section class="contact-form">
        <h2>Get in Touch</h2>
        <form action="submit_contact.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Apartment Listings. All Rights Reserved.</p>
    </footer>
</body>
</html>
