<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mentorship Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Mentorship Platform</h1>
        <!-- Navigation links -->
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <!-- Add more navigation links as needed -->
            </ul>
        </nav>
    </header>
    
    <!-- Main content -->
    <main>
        <!-- Hero section -->
        <section id="home">
            <div class="hero-content">
                <h2>Welcome to the Mentorship Platform</h2>
                <p>Connect with mentors, collaborate on projects, and grow together.</p>
                <a href="#signup" class="btn">Sign Up</a>
            </div>
        </section>

        <!-- Sign up form -->
        <section id="signup">
            <h2>Sign Up</h2>
            <form>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>

                <button type="submit" class="btn">Submit</button>
            </form>
        </section>

        <!-- About section -->
        <section id="about">
            <h2>About Us</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla quam velit, vulputate eu pharetra nec, mattis ac neque.</p>
        </section>
    </main>

    <!-- Footer -->
    <footer id="contact">
        <p>Contact us: mentorship@example.com</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
