<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afrolightment Production</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: url('https://via.placeholder.com/1200x300') no-repeat center center/cover;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            position: relative;
        }
        header::before {
            content: '';
            background: url('https://via.placeholder.com/50') repeat;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            color: #f4a261;
        }
        .container {
            padding: 2rem;
            max-width: 1200px;
            margin: auto;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x500') no-repeat center center/cover;
            height: 500px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 1rem;
            font-size: 2.5rem;
        }
        .section {
            margin-bottom: 2rem;
            background: url('https://via.placeholder.com/100') repeat;
            padding: 1rem;
            border-radius: 8px;
        }
        .clothing-lines {
            display: flex;
            gap: 1rem;
        }
        .clothing-lines div {
            background: #fff;
            padding: 1rem;
            flex: 1;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        .clothing-lines div::after {
            content: '';
            background: url('https://via.placeholder.com/50') no-repeat;
            position: absolute;
            bottom: 0;
            right: 0;
            width: 50px;
            height: 50px;
        }
        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 1rem;
            background: url('https://via.placeholder.com/50') repeat;
        }
    </style>
</head>
<body>
    <header>
        <h1>Afrolightment Production</h1>
        <p>Stories of Black Excellence & Cultural Legacy</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#documentaries">Documentaries</a>
        <a href="#clothing-lines">Clothing Lines</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>Celebrating Black Narratives Worldwide</h1>
    </div>

    <div class="container">
        <section id="about" class="section">
            <h2>About Us</h2>
            <p>Afrolightment Production is a documentary company dedicated to amplifying Afrocentric stories through compelling visual storytelling. Our mission is to celebrate and preserve the diverse cultures of the African diaspora while fostering global understanding.</p>
        </section>

        <section id="documentaries" class="section">
            <h2>Our Documentaries</h2>
            <p>Explore our groundbreaking films that capture the beauty, resilience, and vibrancy of African and African-American communities worldwide.</p>
        </section>

        <section id="clothing-lines" class="section">
            <h2>Clothing Lines</h2>
            <div class="clothing-lines">
                <div>
                    <h3>Eledumare Threads</h3>
                    <p>Celebrating Afrocentric fashion with bold, vibrant designs that honor the essence of African heritage and style.</p>
                </div>
                <div>
                    <h3>Legacy Wear</h3>
                    <p>A collection that connects the past, present, and future through timeless Afro-inspired designs.</p>
                </div>
                <div>
                    <h3>Roots Revival</h3>
                    <p>Earthy, authentic styles inspired by the heartbeat of African culture and tradition.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>We’d love to hear from you! For inquiries about documentaries or our clothing lines, reach out to us at <strong>contact@afrolightment.com</strong>.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Afrolightment Production. All Rights Reserved.</p>
    </footer>
</body>
</html>
