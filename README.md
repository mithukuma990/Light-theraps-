<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Light Therapy X - Professional Landing Page</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        /* Header Styles */
        header {
            background: #2c3e50;
            padding: 1rem 0;
        }

        .logo {
            color: white;
            font-size: 24px;
            margin-left: 2rem;
        }

        nav {
            display: flex;
            justify-content: flex-end;
            padding-right: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 2rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #4CAF50;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('your-image.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 1rem 0;
        }

        .btn {
            background: #4CAF50;
            color: white;
            padding: 1rem 3rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1rem;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #45a049;
        }

        /* Features Section */
        .features {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 0 2rem;
        }

        .feature {
            padding: 2rem;
            margin: 1.5rem 0;
            background: #f5f5f5;
            border-radius: 8px;
            display: flex;
            align-items: center;
        }

        .feature-icon {
            font-size: 2.5rem;
            color: #4CAF50;
            margin-right: 2rem;
        }

        .feature-content {
            flex: 1;
        }

        /* Call to Action */
        .cta {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 3rem 0;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 4rem;
        }

        a.footer-link {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 3rem;
            }
            .feature {
                flex-direction: column;
                align-items: flex-start;
            }
            .feature-icon {
                margin-bottom: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="logo">Light Therapy X</div>
            <nav>
                <a href="#features">Features</a>
                <a href="#pricing">Pricing</a>
                <a href="#contact">Contact</a>
                <a href="privacy-policy.html">Privacy Policy</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Innovative Light Therapy Solution</h1>
            <p>Experience the future of light therapy with our cutting-edge technology</p>
            <button class="btn">Explore Now</button>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="feature">
            <div class="feature-icon">💡</div>
            <div class="feature-content">
                <h2>Advanced Technology</h2>
                <p>Our state-of-the-art light technology provides unmatched precision and effectiveness.</p>
            </div>
        </div>

        <div class="feature">
            <div class="feature-icon">🔬</div>
            <div class="feature-content">
                <h2>Clinically Proven Results</h2>
                <p>Backed by scientific research and approved by leading dermatologists worldwide.</p>
            </div>
        </div>

        <div class="feature">
            <div class="feature-icon">🌟</div>
            <div class="feature-content">
                <h2>User-Friendly Design</h2>
                <p>Intuitive interface makes it easy to customize your light therapy experience.</p>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="cta">
        <h2>Ready to Transform Your Experience?</h2>
        <button class="btn">Start Your Journey</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Light Therapy X. All rights reserved.</p>
        <a href="privacy-policy.html" class="footer-link">Privacy Policy</a>
        <a href="#" class="footer-link">Terms of Service</a>
    </footer>
</body>
</html>
