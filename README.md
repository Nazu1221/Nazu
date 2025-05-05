<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexus Dynamics | Digital Solutions</title>
    <style>
        :root {
            --primary: #6e48aa;
            --secondary: #9d50bb;
            --dark: #1a1a2e;
            --light: #f1f1f1;
            --accent: #ff7e5f;
        }
        body {
            font-family: 'Montserrat', sans-serif;
            background: var(--dark);
            color: var(--light);
            margin: 0;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            padding: 2rem;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }
        h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 2px;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 1rem;
            background: rgba(26, 26, 46, 0.8);
        }
        nav a {
            color: var(--light);
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s;
        }
        nav a:hover {
            color: var(--accent);
        }
        .hero {
            height: 60vh;
            background: url('https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(26, 26, 46, 0.7);
        }
        .hero-content {
            z-index: 1;
            max-width: 800px;
            padding: 2rem;
        }
        .btn {
            background: var(--accent);
            color: var(--dark);
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 50px;
            font-weight: 600;
            cursor: pointer;
            transition: 0.3s;
            text-decoration: none;
            display: inline-block;
            margin-top: 1rem;
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .service-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 2rem;
            border-radius: 10px;
            transition: 0.3s;
        }
        .service-card:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.1);
        }
        footer {
            background: rgba(0, 0, 0, 0.5);
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>NEXUS DYNAMICS</h1>
        <p>Digital Solutions for the Modern Era</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#store">Store</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero" id="home">
        <div class="hero-content">
            <h2>Elevate Your Digital Presence</h2>
            <p>Premium freelance services and digital marketing solutions tailored to your needs.</p>
            <a href="#store" class="btn">Explore Services</a>
        </div>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service-card">
                <h3>Freelance Development</h3>
                <p>Custom web and app development solutions for your business.</p>
            </div>
            <div class="service-card">
                <h3>Digital Marketing</h3>
                <p>Boost your online presence with our targeted marketing strategies.</p>
            </div>
            <div class="service-card">
                <h3>Creative Design</h3>
                <p>Stunning visuals that capture your brand's essence.</p>
            </div>
        </div>
    </section>
    <section id="store">
        <h2>Store</h2>
        <p>Coming soon - Digital products and resources to grow your business.</p>
        <a href="#" class="btn">Notify Me</a>
    </section>
    <section id="blog">
        <h2>Latest from the Blog</h2>
        <div class="services">
            <div class="service-card">
                <h3>Freelancing in 2024</h3>
                <p>How to thrive as a freelancer in the current market.</p>
                <a href="#" class="btn">Read More</a>
            </div>
            <div class="service-card">
                <h3>SEO Myths Debunked</h3>
                <p>The truth about search engine optimization today.</p>
                <a href="#" class="btn">Read More</a>
            </div>
        </div>
    </section>
    <footer id="contact">
        <p>© 2024 Nexus Dynamics. All rights reserved.</p>
        <p>Contact: hello@nexusdynamics.com</p>
    </footer>
</body>
</html>
