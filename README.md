# Landing-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Landing Page</title>
</head>
<body>
    <nav>
        <div class="nav-container">
            <div class="logo">MyWebsite</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#signup">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <header id="home" class="home-section">
        <h1>Welcome to Our Website</h1>
        <p>Your go-to place for amazing content.</p>
    </header>

    <main>
        <section id="about" class="body-section">
            <h2>About Us</h2>
            <p>Learn more about what we do and our mission.</p>
        </section>

        <section id="contact" class="body-section">
            <h2>Contact Us</h2>
            <p>Get in touch with us for more information.</p>
        </section>

        <section id="signup" class="signup-section">
            <h2>Sign Up</h2>
            <form action="#" method="POST">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <input type="password" placeholder="Your Password" required>
                <button type="submit">Sign Up</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 MyWebsite. All rights reserved.</p>
    </footer>
</body>
</html>

CSS
/* Reset some default styles */
body, h1, h2, p, ul, li, a, input, button {
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

nav {
    background-color: #333;
    color: #fff;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
}

.logo {
    font-size: 24px;
}

.nav-links {
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: #fff;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #f0f0f0;
}

header {
    background-color: #f4f4f4;
    padding: 60px 0;
    text-align: center;
}

header h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

header p {
    font-size: 18px;
    color: #555;
}

.body-section {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
}

.body-section h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.signup-section {
    max-width: 400px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    text-align: center;
}

.signup-section input, .signup-section button {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.signup-section button {
    background-color: #333;
    color: #fff;
    cursor: pointer;
    transition: background-color 0.3s;
}

.signup-section button:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
