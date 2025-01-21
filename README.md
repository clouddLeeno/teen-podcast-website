# teen-podcast-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creaming Up the Teen Scene: Youthful Glow</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #FFD700, #FF69B4, #87CEEB);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            color: #333;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        header {
            text-align: center;
            padding: 1rem;
            background-color: rgba(255, 255, 255, 0.8);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0.5rem;
            color: #444;
        }

        nav {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.1);
            padding: 1rem 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        nav a:hover {
            color: #FF69B4;
        }

        section {
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .subscribe, .social, .contact {
            margin-top: 2rem;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: rgba(255, 255, 255, 0.8);
            margin-top: 2rem;
        }

        footer p {
            margin: 0;
            font-size: 0.9rem;
        }

        input[type="email"] {
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-right: 5px;
        }

        button {
            padding: 0.5rem 1rem;
            border: none;
            background-color: #87CEEB;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #FFD700;
        }
    </style>
</head>
<body>
    <header>
        <h1>Creaming Up the Teen Scene: Youthful Glow</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#episodes">Episodes</a>
        <a href="#subscribe">Subscribe</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About the Podcast</h2>
        <p>Welcome to "Creaming Up the Teen Scene: Youthful Glow," a podcast where we dive into themes of resilience, identity, and memory. Designed for teenagers, each episode aims to inspire, educate, and empower young minds. Join us on this journey!</p>
    </section>

    <section id="episodes">
        <h2>Podcast Episodes</h2>
        <p>Check out our latest episodes below:</p>
        <ul>
            <li>Episode 1: <em>The Power of Resilience</em></li>
            <li>Episode 2: <em>Understanding Identity</em></li>
            <li>Episode 3: <em>Honoring Memory</em></li>
        </ul>
    </section>

    <section id="subscribe" class="subscribe">
        <h2>Subscribe for Updates</h2>
        <p>Enter your email to stay updated on new episodes:</p>
        <form>
            <input type="email" placeholder="Your email address" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need professional help, feel free to reach out:</p>
        <p>Instagram: <a href="https://www.instagram.com/leennmansourr" target="_blank">@leennmansourr</a></p>
        <p>Phone: <a href="tel:0790478481">0790478481</a></p>
        <p>Professional Help: <a href="tel:0777722262">07 7772 2262</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Creaming Up the Teen Scene: Youthful Glow. All rights reserved.</p>
    </footer>
</body>
</html>
