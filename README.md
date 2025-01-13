<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohave Desert Adventures | Unique Desert Expeditions</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f9f6f1;
            color: #2c1810;
        }

        .header {
            background-color: #8b4513;
            color: #f9f6f1;
            padding: 1.5rem;
            text-align: center;
        }

        .nav {
            background-color: #654321;
            padding: 1rem;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        .nav a {
            color: #f9f6f1;
            text-decoration: none;
            font-weight: bold;
        }

        .nav a:hover {
            color: #ffd700;
        }

        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 6rem 2rem;
            text-align: center;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .main-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .feature-card {
            background-color: #fff;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .cta-button {
            display: inline-block;
            padding: 1rem 2rem;
            background-color: #ffd700;
            color: #2c1810;
            text-decoration: none;
            border-radius: 5px;
            margin: 1rem 0;
            font-weight: bold;
            text-transform: uppercase;
        }

        .cta-button:hover {
            background-color: #ffed4a;
            transform: translateY(-2px);
            transition: all 0.3s ease;
        }

        .footer {
            background-color: #8b4513;
            color: #f9f6f1;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }

        .highlight {
            color: #8b4513;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            .nav {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Mohave Desert Adventures</h1>
        <p>Discover Hidden Treasures of the Desert</p>
    </header>

    <nav class="nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#adventures">Adventures</a>
        <a href="#experience">The Experience</a>
        <a href="#contact">Book Now</a>
    </nav>

    <section class="hero">
        <h2>Your Ultimate Desert Adventure Awaits</h2>
        <p>Exclusive 3-hour Jeep expeditions through the mysterious Mohave Desert</p>
        <a href="#contact" class="cta-button">Book Your Adventure</a>
    </section>

    <main class="main-content">
        <section id="about">
            <h2>Welcome to the Real Desert Experience</h2>
            <p>At Mohave Desert Adventures, we offer more than just a tour – we provide an authentic journey into the heart of the desert. As your experienced guide, I bring intimate knowledge of the land and its hidden treasures, taking you beyond the typical tourist trails to discover the true spirit of the Mohave.</p>
        </section>

        <section id="adventures" class="features">
            <div class="feature-card">
                <h3>Expert Local Knowledge</h3>
                <p>With years of experience and deep understanding of the Mohave Desert's terrain, I'll guide you to hidden gems and share stories that you won't find in any guidebook. From secret historical sites to breathtaking viewpoints, every adventure is unique.</p>
            </div>
            <div class="feature-card">
                <h3>Custom Adventures</h3>
                <p>Each expedition is tailored to your interests. Whether you're passionate about history, geology, or simply seeking adventure, we'll create an itinerary that perfectly matches your desires. Every trip is different, making each experience truly special.</p>
            </div>
            <div class="feature-card">
                <h3>Primitive Cooking Experience</h3>
                <p>Experience the authentic desert lifestyle with our unique outdoor cooking adventure. Learn to build a cooking fire and prepare your own meal under the vast desert sky – a perfect blend of adventure and traditional desert living.</p>
            </div>
        </section>

        <section id="experience">
            <h2>What to Expect</h2>
            <ul style="list-style: none; margin: 2rem 0;">
                <li>✦ 3-hour off-road Jeep adventure</li>
                <li>✦ Exclusive access to hidden historical sites</li>
                <li>✦ Expert guidance and storytelling</li>
                <li>✦ Traditional desert cooking experience</li>
                <li>✦ Small group sizes for personalized attention</li>
                <li>✦ Customized routes based on your interests</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Book Your Desert Adventure</h2>
            <p>Ready to explore the hidden wonders of the Mohave Desert? Contact us to plan your unique adventure:</p>
            <p class="highlight">Phone: [Your Phone Number]</p>
            <p class="highlight">Email: [Your Email]</p>
            <p>Available for morning and afternoon expeditions</p>
            <a href="#" class="cta-button">Reserve Your Journey</a>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Mohave Desert Adventures. All rights reserved.</p>
        <p>Licensed and insured desert expedition service</p>
    </footer>
</body>
</html>
Adventure service llc 
